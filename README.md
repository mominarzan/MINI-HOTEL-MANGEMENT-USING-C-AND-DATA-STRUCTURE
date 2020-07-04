                 MINI-HOTEL MANGEMENT USING C AND DATA STRUCTURE
                 
                 
                 
                 Introduction

Every major buisness requires storing information of clients, our idea aims to store clients data using data structures. In this project we have aimed at providing this service as Database management of a hotel. Our program takes in username, Mobile number and email id as input, and can perform various operations such as storing, modification, displaying, and deletion. Since we are using the concept of files and linked list we are able to store data efficiently and safely without risking much data loss.
The program involves creating an object Room using “struct” keyword and creating a file contactdatabase.bat to store the clients data. We display the various  operations that the user has using DO-While loop. We created functions for each method and each prompt. Using switch case we accept input and select the series of functions that has to be executed. The storing is done using linked list and File Handling. The linked list has 3 components
i)firstc:- Contains the first record.
ii)currentc:-Points to the current record in list.
iii)newc:- contains address of new node.
The program contains the following functions:-
addNewroom(Return type:-void; Parameter:-void):- Creates a new entry in the list, the function checks whether the entry is the first entry if so sets al nodes(i.e currentc and newc) to firstc. Else the end of the list is obtained and the new entry is added there.
listAll(Return type:-void;Parameters:- void):- Displays the all the entries made by simply traversing the linked list.
deleteRoom(Return type:- void;Parameters:- void):-Frees memroy allocated to the node be usinf free().
modifyRoom(Return type:-void;Parameters:- void):-uses user defined listAll() function to display all records. Searches a perticular record using another user defined function findum(). Once found asks the user for modifications.
int findnum (Return Type:- int;Parameters:-int recordnum):- Traverses the list using if-Else statement searches the required element using room number.
findroom(Return Type:-integer;Parameters:-void):- Traverses the list for a matching name as entered by the user(Case sensitive) if found returns their details.
prompt(Return Type:- integer;Parameters:-void):-This function is executed after the function modifyRoom(), this function acts as a prompt which asks if the user wants to modify any details. 
 

       Algorithm:

 Step 1: START 

 Step 2: Delare  Functions that are requried in program
  void clearInput(void),    void addNewroom(void),    void listAll(void)   void deleteroom(void),
             void modifyroom(void),   int findroom(void),   int prompt(void),   int findnum (int).
Step 3: Define Struct room
Containing  int number ( unique room number),   char name[20](contains name),char phone[15]
          (contains phone number),   char email[20] (contains email address)  also *next pointer
Step 4 :   create file 
              declare file name, open file for reading, make record by using struct, pointer referencing next node,               close file 
Step 5:    print menu messages
              Use switch case for menu selection and call the function requried
Step 6: define the functions 
void addNewroom(void) take the room records from the user by using struct room
void listAll(void)  display all the room records available in the file
void deleteroom(void)  show all room number then take room no. from the user that has to be delete. Remove the records of that room no 
void modifyroom(void) modify the room detail of specified room no entered by user
int findroom(void) find room records by name specified by user

step 8: STOP

 

 



3.5 Conclusion:
This program helps us to understand the concept of singly link list, dynamic memory allocation in data structure, various other concepts of  Data Structure using c  
3.5 Future Scope:
•	Generally, we have seen that data structure is extensively used for database development and management, Searching data, operating system, developing video games etc.
•	But do you know there are some future technologies that are relying on data structure? As a matter of fact, data structure has become very famous .Let’s dive into the technologies which use data structure as a core element for research, production and further developments.


          
                 
