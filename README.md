Interface IEmployee:
public interface IEmployee {
    int calculateSalary();
    String getName();
}
Class Employee:
public class Employee implements IEmployee {
    private String name;
    
    public Employee(String name) {
        this.name = name;
    }
    
    @Override
    public int calculateSalary() {
        // Implement the salary calculation logic here
        return 0;
    }
    
    @Override
    public String getName() {
        return name;
    }
}
