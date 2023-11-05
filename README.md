## Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:
## step 1:
Create a base class.

## step 2:
Create two child class.

# step 3:
Create a constructor in the base class and print a message.

# step 4:
create a function in child class to print a message.

## Program:
~~~
using System;
namespace Wheel{
    public class Tyre{
        public Tyre(){
            Console.WriteLine("Tyre for Vehicles");
        }  
    }
    public class Scooter: Tyre{
        public void DisplayScooter(){
            Console.WriteLine("2 Tyre for scooters");
        }
    }
    public class Car: Tyre{
        public void DisplayCar(){
            Console.WriteLine("4 Tyre for Car");
        }
    }
    public class Program{
        public static void Main(string[] args){
            Car c = new Car();
            c.DisplayCar();
            Console.WriteLine();
            Scooter s = new Scooter();
            s.DisplayScooter();   
        }
    }
}
~~~

## Output:
![image](https://github.com/sasidharan403/Inheritance/assets/94154712/d44c7c5a-ff00-40c5-bc06-33cfe8d11b7d)



## Result
Thus, C# program to print some messages using hierarchical inheritance is implemented successfully.
