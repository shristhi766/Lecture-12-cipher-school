# Lecture-12-cipher-school
package accessModifiers2;
import accessModifers1.A;
public class D{
    public static void main(String[] args){
            A obj = new A();
            System.out.println(obj.x);
            System.out.println(obj.y);
             System.out.println(obj.z);
              System.out.println(obj.w);
package encapsulation;
class Demo{
    private int a = 5;
    private int b = 10;
    private int c = 15;
    private int d = 20;
    public int getA(){
           System.out.println("Value of A read");
            return  this.a;
    }
    public  int getB()
    {
         System.out.println("Value of B read");
          return this.b;
          
    }
    public void setA(int a)
    {
          if(a>100);
          {
          this.a = a;
          System.out.println("Value of A changed to:"+a);
    }else{
         System.out.println("Cannot set - value outside limits");
    public void setB(int b)
    {
          this.b = b;
}
//* public void setB(int b)
  {
     this.b = b;
   }
   public int getC()
   {
        return c;
    }
    public void setD(int d)
    {
        this.d = d;
      }
}
public class EncapStudy{
       public static void main(String[] args){
       Demo d = mew Demo();
       System.out.println(d.getA());
       d.setA(100),
       System.out.println(d.getA());
    }
  }
