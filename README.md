-1 
1 / 45
Which of the following are advantages of encapsulation?

The are 2 correct answers

A. Private data can be accessed easily without getters and setters
B. Private data can be changed without creating an object
x C. Read only/Write-only data can be defined in a class
x D. The data stored in fields can be controlled by the class easily

__________________________________________________
2 / 45
What will the following code snippet print?

int index = 1;

String[] strArr = new String[5];

String  myStr  = strArr[index];

System.out.println(myStr);

The are 1 correct answers

It will print nothing.
x It will print null.
It will throw ArrayIndexOutOfBoundsException at runtime.
It will print some junk value.
None of the above.



_____________________________________________________

3 / 45
3 / 45
What will be the output of the following program?

public class LoopingTest

{

   public static void main(String args[])

   {

      int i;

      int j=2;

      for (i = 0; i > 5 ; i++)

      {

         System.out.print(i*j);

      }

   }

}

The are 1 correct answers

A. Prints 0 2 4 6 8
B. Prints 0 1 3 4 5
C. Compilation error
x D. Prints nothing
E. Throws RuntimeException

_____________________________________________________

4 / 45
Which of the following statements correctly use the float data type?
The are 1 correct answers

var float x = 10.0;
float x : 10.0;
x float x = 10.0F;
float x : 10.0F;
var float f = 10.0f;

__________________________________________________

- 5. 

5 / 45
What will be the output of the following code?

public class Q14 {

    public static void switchTest(int j) {

       switch (j) {

       case 1:

           j++;

       case 2:

           j++;

       case 3:

           j++;

       case 4:

           j++;

       case 5:

          j++;

       default:

           j--;

       }

       System.out.println(j);

    }

    public static void main(String[] args) {

       switchTest(2);

    }

}

The are 1 correct answers

x A. 5
B. 4
C. 2
D. 1
E. 3


___________________________________________________-

6 / 45
Which of the following statements are true?
The are 2 correct answers

A static method can call other non-static methods in the same class by using the ‘this’ keyword.
x A class may contain both static and non-static variables and both static and non-static methods.
Every object of a class has its own instance of each non-static member variable.
x Instance methods may access local variables of static methods.
All methods in a class are implicitly passed a ‘this’ parameter when called.;




___________________________________________________

7 / 45
What will be the result?

List<Double> list = new ArrayList<>();

System.out.println(list.get(list.size())); // Line 1

list.add(1); // Line 2

System.out.println(list.indexOf(1.0)); // Line 3

The are 1 correct answers

x A. Does not compile
B. Throws exception at line 1
C. Throws exception at line 2
D. Throws exception at line 3





___________________________________________________

8 / 45
Which of the following statements is true about ArrayList?

The are 1 correct answers

A. Is always thread-safe
B. Is of fixed size
C. Element access is faster than in arrays
x D. Can be sorted by using the sort() method of the Collections class






___________________________________________________

9 / 45
public class Q13 {

    private static String Q13; // 1

    public Q13(String Q13) {

    } // 2

    public void Q13() {

    } // 3

        private Q13() {

    } // 4

}

The are 1 correct answers

A. Compilation error at line 1
x B. Compilation error at line 2
C. Compilation error at line 3
D. Compilation error at line 4
E. Compiles fine




___________________________________________________

10 / 45
Which of the following declarations of the main method always allow the class to be run as an application?

The are 3 correct answers

x A. final public static void main(String[] args)
B. static void main(String[] args)
C. public void static main(String[] args)
D. public static main(String[] args)
x E. public static void main(String[] args)
x F. static public void main(String[] args)



___________________________________________________
11 / 45
What happens when you try to compile and run the following program?

public class CastTest

{

   public static void main(String args[ ] )

   {

      byte b = -128 ;

      int i = b ;

      b = (byte) i;

      System.out.println(i+” “+b);

   }

}

The are 1 correct answers

The compiler will refuse to compile it , as i and b are of different types cannot be assigned to each other.
x The program will compile and will print -128 and -128 when run .
The compiler will refuse to compile it , since -128 is outside the legal range of values for a byte.
The program will compile and will print 128 and -128 when run .
The program will compile and will print 255 and -128 when run .

___________________________________________________
12 / 45
Which of the following statements are used to implement a boolean conditional statement in Java?
The are 2 correct answers

x if
try-catch
x if-else
if-case
switch
for




___________________________________________________


13 / 45
What will be the result of attempting to compile and run the following code?

class SwitchTest

{

   public static void main(String args[])

   {

      for ( int i = 0 ; i < 3 ; i++)

      {

         boolean flag  = false;

         switch (i)

         {

            flag  = true;

         }

         if ( flag )  System.out.println( i );

      }

   }

}

The are 1 correct answers

It will print 0, 1 and 2.
It will not print anything.
x Compilation error.
Runtime error.
None of the above.




___________________________________________________

14 / 45
Which of the given options can be successfully inserted at line 1….

//line 1

public class A

{

}

The are 3 correct answers

x import java.lang.*;
x package p.util;
x public class MyClass{ }
class MyClass{ }




___________________________________________________

15 / 45
What will be the result of the below code snippet?

List<String> list = new ArrayList<String>();

list.add("apple");

list.add("mango");

list.add("apple");

list.add("orange");

System.out.println(list.remove("Apple"));
The are 1 correct answers

A. Does not compile
B. Prints “true”
C. Prints 1
D. Prints 2
E. Prints 0
x F. Prints “false”



___________________________________________________

16 / 45
Which is the value range of an int variable?

The are 1 correct answers

A. -2^32 to 2^32-1
x B. -2^31 to 2^31-1
C. -2^32 to 2^32
D. -2^31 to 2^31
E. None of the above







___________________________________________________

Which of the following classes are from java.util package?
The are 3 correct answers

String
x ArrayList
x Collection
Math
x Random







___________________________________________________



18 / 45
Which of the following features are provided by a JDK?
The are 2 correct answers

Networking protocols
Versioning control system
x Development tools
IDE





___________________________________________________



19 / 45
What will be the output of the following code?

public class Q15 {

    public static int main(String[] args) {

       System.out.println("Hello World");

       return 0;

    }

}

The are 1 correct answers

A. Prints “Hello World
B. Prints nothing
C. Does not compile
x D. Does not run
E. Throws an exception 






___________________________________________________


20 / 45
Which of the following are valid constructors for the given class Q24?

 

public class Q24 {

 

}

 

The are 2 correct answers
x A. Q24() {

             }
B. public final Q24(int i) {

            }
x C. private Q24(int i, char j) {

             }
D. public synchronized Q24(int i) {

            }
E. public void Q24(int i) {

            }
F. public static Q24(int i) {

            }








___________________________________________________
- 21. 
What will be the output of the following code?

public class Q12 {

    public static void main(String[] args) {

       outer: for (int i = 0; i < 2; i++) {

           for (int j = 0; j < 2; j++) {

               if (i == j) {

                   continue outer;

               }

               System.out.println("i=" + i + ", j=" + j);

           }

       }

    }

}

The are 1 correct answers

A. i=0, j=1
B. i=1, j=1
x C. i=1, j=0
D. Nothing is printed










___________________________________________________


22 / 45
Which of the lines will cause a compile time error in the following program?

public class MyClass

{

   public static void main(String args[])

   {

      char c;

      int i;

      c = ‘a’;//1

      i = c;  //2

      i++;    //3

      c = i;  //4

      c++;    //5

   }

}

The are 1 correct answers

The line 1
The line 2
The line 3
x The line 4
The line 5







___________________________________________________
23 / 45
What can be inserted in the following code so that it will print exactly 2345 when compiled and run?
public class FlowTest {

static int[] data = {1, 2, 3, 4, 5};

public static void main(String[] args) {

for (int i : data) {

if (i < 2) {

//insert code1 here

}

System.out.print(i);

if (i == 3) {

//insert code2 here

}

}

}

}

The are 2 correct answers
break;
and
//nothing is required

x continue;
and
//nothing is required

continue;
and
continue;

break;
and
continue;

break;
and
break;






___________________________________________________

24 / 45
Which of the following keywords are related to exception handling?

The are 3 correct answers

x A. finally
B. switch
x C. throws
x D. throw
E. continue


___________________________________________________
25 / 45
Which access modifier specifies that an instance variable can only be accessed within its own package or by a subclass of its class in another package?

The are 1 correct answers

A. private
x B. protected
C. public
D. No modifier




___________________________________________________

26 / 45
Which of the following options will cause a compiler error when inserted at line 1?

public class QTest {

    public void draw(String s) { 

    }

    public String draw(int i) { 

    }

    public void draw(int i, double f) {

    }

    public void draw(int i, long f) {

    }

// Add code here - line 1

}
The are 2 correct answers

x A. public void draw(StringBuilder s) { }
B. public void draw(int a, long b) { }
x C. public void draw(Object o) { }
D. public int draw(int f) { }


___________________________________________________
27 / 45
Given the following LOCs:

int i = 0;

char ch = ‘a’;

Which of the following will put correct integer value of the char variable ch into the int variable i?

The are 3 correct answers
x i = ch ;
x i = (int) ch ;
i << ch ;
i <<< ch
x i += ch;
i := ch;



___________________________________________________

28 / 45
What will be the output of the following program?

class  A {

   public abstract String abstractMethod();

}

class B extends A{

    @Override

    public String abstractMethod() {       

        return "Abstract Method";

    }   

}

public class StaticTest {

    public static void main(String[] args) {

        B b=new B();

        System.out.println(b.abstractMethod());

    }

}

The are 1 correct answers

A. Prints “Abstract Method”
x B. Compilation error
C. Exception at runtime 
D. Prints nothing
E. Can’t override abstract method



___________________________________________________
29 / 45
Which of the following correctly assigns a null reference to an object?

The are 1 correct answers
A. Integer i=new Integer(null);
B. Long l=NULL;
x C. String s1=null;
D. Object o->null;
E. String s2=””;



___________________________________________________

30 / 45
Given the following class, which statements can be inserted at line 1 without causing the code to fail compilation?

public class TestClass

{

   int a;

   int b = 0;

   static int c;

   public void m()

   {

      int d;

      int e = 0;

      // Line 1

   }

}

The are 4 correct answers

a++;
x b++;
x c++;
d++;
x e++;

___________________________________________________

31 / 45
What will the following program print?

public class TestClass

{

   public static void main(String[] args)

   {

      String str = “111”;

      boolean[] bA = new boolean[1];

      if( bA[0] ) str = “222”;

      System.out.println(str);

   }

}

The are 1 correct answers

x 111
222
It will not compile as bA[0] is uninitialized.
It will throw an exception at runtime.
None of the above.



___________________________________________________
32 / 45
Which package contains Random class?
The are 1 correct answers

java.lang
x java.util
java.math
java.net


___________________________________________________
33 / 45
Which of the following are keywords in Java?

The are 3 correct answers

A. threw
x B. new
C. exit
x D. instanceof
E. unsigned
x F. enum



___________________________________________________

34 / 45
What will be the output of the following program?

public class QTest {

    public static void main(String args[]) {

        int i = 0;

        int j = 0;

      for (i = 1; i <= 10; i++,j++) {

            if (i == 5) {

                // breaking the loop

               break;

            }

        }

        System.out.println(i+" "+j);

    }

}

The are 1 correct answers

x A. Prints 5 4
B. Compilation error
C. Prints 4 5
D. Prints 9
E. prints 4 4


___________________________________________________

35 / 45
Consider the following code:
public class Varargs

{

   public void test()

   {

        test1(10);       //1

        test1(10, 20); //2

   }

   public static void main(String[] args)

   {

     new Varargs().test();

   }

   

   //insert method here.

}

Which of the following lines can be added independently to the above class so that it will run without any errors or exceptions?

The are 2 correct answers

x public void test1(int i, int j){}
public void test1(int i, int… j){}
x public void test1(int… i){}
public void test1(int i…){}
public void test1(int[] i){}

___________________________________________________
36 / 45
Given:

class Node{

int id;

Node node;

public static void main(String[] args) {

Node n =  new Node();

System.out.println(n.id);

System.out.println(n.node.id);

}

}

What is the result?

The are 1 correct answers
0,0
x 0, null
0, exception at runtime
Compilation failure


___________________________________________________

37 / 45
Consider the following two java files:

//in file SM.java

package x.y;

public class SM

{

    public static void foo(){ };

}

//in file TestClass.java

//insert import statement here //1

public class TestClass

{

   public static void main(String[] args)

   {

      foo();

   }

}

What should be inserted at //1 so that TestClass will compile and run?

The are 2 correct answers

import static x.y.*;
import static x.y.SM;
x import static x.y.SM.foo;
import static x.y.SM.foo();
x import static x.y.SM.*;

___________________________________________________


38 / 45
Which of the following options will print a Random number between 0 and 20?

 

int seed = 15;

 

//insert code here

 

System.out.println(d);

The are 1 correct answers
x A. Random random = new Random(seed);

    int ranInt = random.nextInt();
B. Random random = new Random(seed);

    int ranInt = random.setSeed(seed);
C. Random random = new Random();

    int ranInt = random.nextInt(seed);
 D. Random random = new Random();

    int ranInt = random.nextInt(seed*20);





___________________________________________________
39 / 45
What will be the output of the following code?

public class QTest {

    public static void main(String args[]) {

        try {

            int nos[]=new int[2];

            nos[5]=100;

            System.err.println(nos[5]);

        } catch (Exception e) {

          e.printStackTrace();

        } 

        catch (ArrayIndexOutOfBoundsException a) {

           e.printStackTrace();



        }      

    }

}

The are 1 correct answers

A. Prints 100
B. It will be caught by the ArrayIndexOutOfBoundsException catch block
x C. The code will not compile
D. It will be caught by the Exception catch block
E. None of the above


___________________________________________________

40 / 45
Which of the following are true about the default constructor?

The are 2 correct answers

x A. If no constructor is added to a class, the class gets a default constructor
B. The default constructor may or may not have parameters
C. Every class gets a default constructor
x D. The default constructor of a class always calls the no-argument constructor of the superclass


___________________________________________________

41 / 45
Which line, if any, will give a compile time error ?

void test(byte x)

{

   switch(x)

   {

      case ‘a’:   // 1

      case 256:   // 2

      case 0:     // 3

      default :   // 4

      case 80:    // 5

   }

}

The are 1 correct answers

Line 1 as ‘a’ is not compatible with byte.
x Line 2 as 256 cannot fit into a byte.
No compile time error but a run time error at line 2.
Line 3 as the default label must be the last label in the switch statement.
There is nothing wrong with the code.



___________________________________________________

42 / 45
Analyze the following code and pick the correct statement.

 

Random random = new Random();

 

System.out.println(random.nextInt(50));

The are 1 correct answers
A. Prints an Integer > 0 and <=50
x B. Prints an Integer >= 0 and <50
C. Prints an Integer >= 1 and <=49
D. Prints all Integers upto 50
E. Prints 1 to 50



___________________________________________________

43 / 45
Given the following code. Which of the following is legal?

public class Q19 {

    int a;

    static int b;

    public void method1() {

       int c = 5;

       b=this.a;

       this.a=c;

       this.a=b;

       //this=new Q1();

       //this.c=4;        

    }

}

The are 3 correct answers

xA. b=this.a;
x B. this.a=c;
C. this=new Q1();
D. this.c=4;
x E. this.a=b;




___________________________________________________


44 / 45
Given the class

// Filename: Test.java

public class Test

{

   public static void main(String args[])

   {

      for(int i = 0; i< args.length; i++)

      {

         System.out.print(”  “+args[i]);

      }

   }

}

Now consider the following 3 options for running the program:


a: java Test

b: java Test param1

c: java Test param1 param2

Which of the following statements are true?

The are 2 correct answers

The program will throw java.lang.ArrayIndexOutofBoundsException on option a.
The program will throw java.lang.NullPointerException on option a.
The program will print Test param1 on option b.
x It will print param1 param2 on option c.
x It will not print anything on option a.



___________________________________________________

45 / 45
Which of the following are advantages of polymorphism?

The are 2 correct answers

A. Security
x B. Reusability
C. Data Hiding
x D. Flexibility