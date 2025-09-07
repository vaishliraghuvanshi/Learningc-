# C# Tutorial Notes

## 1. Download, Install and Setup Visual Studio
- **IDE** – Integrated Development Environment  
- **Visual Studio Installer** – Select **.NET desktop development**  
- For gaming development, select **Unity**  

### Steps:
1. Create new project  
2. Search **ConsoleApp (C#)**  
3. Enter the project name and set location  
4. Select proper framework (**.NET 9.0 or Term**)  

⚠️ Do not tick these options:  
- Do not use top-level statements  
- Enable native AOT publish  

## 2. Manage Extensions
- To install extensions:  
  1. Search in Visual Studio Marketplace  
  2. Install the required extension  
  3. Go to **Tools → Options**  
  4. Find and manage the extension  

## 3. Common Errors in C#
1. **Incorrect Syntax** – Missing `; { }`  
2. **Wrong Case** – `Int` instead of `int`, `True` instead of `true`  
3. **Variable Not Initialized** – Using a variable before assigning a value  
   ```csharp
   int age;
   Console.WriteLine(age); // Error
4.**Cannot Convert Type** – Some types cannot be implicitly converted

float number = 50f;
int age = number; 
5. Incorrect Syntax** 
Example -
if (1 = 1) // Wrong

6.**Different Scope Issue** – Variable exists only inside its scope
Example -
public static void Main(string[] args) {
    int age = 35;
}
private static void MyClass() {
    age++; // Error (not accessible outside Main)
}
7.**Cannot Access Private** – Private members must be public to be accessible.

4. Variables -Containers that store data

Data Types – string, int, bool

Examples of Math Operations:
int age = 35;
age = age + 1;   // 36
age++;           // 37
age = age - 1;   // 34
age = age * 2;   // 70
age = age / 2;   // 17
Console.WriteLine(age);

5. Why Data Types Are Important?

Each variable must have a data type.

The data type defines what kind of value the variable can store.

6. Good Naming Conventions

A good variable name describes exactly what the variable represents.

7. What is Console.WriteLine()?

A function that writes output to the console in C#.

Console.WriteLine("Hello, World!");

8. What if a Variable is Declared but Not Initialized?

If you don’t assign a value, the variable is uninitialized and cannot be used.

int age;
Console.WriteLine(age); // Error: variable 'age' is uninitialized
