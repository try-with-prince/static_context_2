   class New{
 int a;
 public void display(){
  System.out.println("in Test1 class");
 }
}
 class News{
  public static void main(String arg[])
{


System.out.println(New.a);	//non-static variable a cannot be referenced from a static context


  System.out.println("in Test class");
  //Test1 t = new Test1();
  //t.display();
 }
}                           
