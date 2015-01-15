# C# Helpers

Compile file:
msc file_name -o test

Run file and interact:
./test

| File name        		| Description 												   |
| --------------------- |------------------------------------------------------------- |
| 0_hello_world.cs 			| - Hello world to C# |
| 1_variables.cs			| - Using variables |
| 2_data_structures.cs		| - Using basic data structures (Tuple, array, List and dictionary) |
| 3_conditionals.cs			| - Using if and switch-case |
| 4_loops.cs				| - Using loops (While, do and For) |
| 5_functions_methods.cs 	| - Using functions and methods |
| 6_classes.cs 				| - Create Enumeration, Classes and Inheritance |
| 7_libraries.cs 			| - Using libraries (Time, Math and Random) |
| 8_io.cs 					| - Read standard input and manipulate files |
| 9_value_transform.cs		| - Value to string and string to value functions |
| PersonBase.cs				| - Interface created to be exported |
| Person.cs					| - Implement PersonBase class |
| HeroBase.cs				| - Abstract Class created to be exported |
| Hero.cs					| - Extend Class HeroBase class |
| Enemy.cs					| - Generic Template Class |
| 10_importing_files.cs		| - Import files |

Compile the last one using:
mcs PersonBase.cs Person.cs HeroBase.cs Hero.cs 10_importing_files.cpp -o test