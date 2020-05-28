## C Interview questions and answers

 
### Questions On Storage Class Specifier

1. What are storage class specifier?

   Storage class specifiers in C language tells the compiler where to store a variable, how to store the variable, what is the initial value of the variable and life time of the variable.
   
   **Syntax:** `storage_specifier data_type variable _name`

   Types of storage class specifier in c :
   
   There are four storage class specifier in C Language. They are,
   
   1. Automatic
   2. Register
   3. Static
   4. Extern
   
   
   Storage Specifier | Storage Place | Initial /Default value | Scope | Life Time |
   ----------------- | ------------- | ---------------------- | ----- | --------- |
     Auto | CPU Memory | garbage value | local | within block |
     static | CPU Memory | zero | local | Retains the value of the variable between different function calls. | 
     register | CPU Memory | garbage | local | within block | 
     extern | CPU Memory | zero | global | Till the end of the main program. Variable definition might be anywhere in the C program  | 
1. **What is static variable**?

    There are 3 main uses for the static variable.
    1. If it declares within a function: 
       * It retains the value between function calls.
    1. If it is declared for a function name:
       * By default function is extern, so it will be visible from other files if the function  declaration is as static, it is invisible for the outer files.
    1. Static for global variables:
       * By default we can use the global variables from outside files If it is static global..that variable is limited to with in the file.
