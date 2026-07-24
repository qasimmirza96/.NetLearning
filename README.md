SOLID PRINCIPLES OF PROGRAMMING
Solid principles are the set of five principles to write maintain, flexible and easy to understand code. 
S = Single Responsibility Principle.
O = Open/Closed Principle.
L = Liskov Substitution Principle.
I = Interface Segregation Principle.
1. Single repository
A class should have only one reason to change, meaning that a class should have one job to do.

2- open and close 
Components of .NET
1. CLR (Common Language Runtime)

CLR is the engine of .NET.

Its responsibilities:

Runs your program
Manages memory
Handles exceptions
Garbage Collection (GC)
Security
Thread management

Think of CLR as the brain of .NET.

2. CTS (Common Type System)

CTS defines data types.

Examples:

int
string
bool
double
char

Every .NET language follows CTS.

3. CLS (Common Language Specification)

CLS defines rules that every .NET language should follow.

Because of CLS:

C#
VB.NET
F#

can work together.

4. BCL (Base Class Library)

BCL is a huge collection of ready-made classes.

Examples:

Console
Math
DateTime
String
File
List
Dictionary

Instead of writing everything yourself, you use these libraries.

Example:

Console.WriteLine("Hello");

Math.Sqrt(25);

DateTime.Now;
5. Garbage Collector (GC)

GC automatically removes unused memory.

Example:

Student s = new Student();

When s is no longer needed, the Garbage Collector frees its memory automatically.
