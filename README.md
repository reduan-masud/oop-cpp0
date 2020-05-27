## CPP OOP HOMEWORK
Define two class type: **Student** and **Graduate**, where Graduate inherits from student.
Class **Student** includes
(1) member variables: name, id and score (protected)
(2) member functions: (public)
	       
 - a default constructor Student::Student(): name("no name"), id(0), score(0)
 -  constructor [u]Student::Student(string n, int i, double s):name(n) id(i), score(s)
 -  void output()

Class **Gradute** has
(1) additional member variable ***string*** **superVisor(*private*)**
(2) additional member function: **(public)**
 - a default constructor **Graduate::Graduate(): Student(), superVisor("No Name")**
 - a constructor **Graduate:: Graduate(string n, int i, double s, string sn): Student(n, i, s), suberVisor(sn)**
 - **void output()** -- redefine function
### Define three graduate student g1, g2, g3 in main function
1. Input the information for g1 from the keyboard
2. Initialize the information for g2 when it is declared (using default constructor)
3. Initialize the information for g3 when it is declared (using normal constructorii)

##[NOTE] 
input: name(string) id(string) score(float) name(string)

