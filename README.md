# Inheritance-Ex2


class A{
    private int x;
    void setx(int x1)
    {
        x=x1;
    }
    void displayx()
    {
        System.out.println(x);
    }
}
class B extends A {
    private int y;
    void sety(int y1)
    {
        y=y1;
    }
    void displayy()
    {
        System.out.println(y);
    }
    
}

public class ABTest {
    public static void main(String args[]) {
    B b1=new B();
    b1.setx(5);
    b1.sety(10);
    b1.displayx();
    b1.displayy();
        
    }
}
