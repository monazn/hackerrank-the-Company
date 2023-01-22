# hackerrank-the-Company
Amber's conglomerate corporation just acquired some new companies. Each of the companies follows this hierarchy: 

![image](https://user-images.githubusercontent.com/56919626/213913043-ccce15b8-3b8e-4012-81c7-540959b6d4ff.png)


Given the table schemas below, write a query to print the company_code, founder name, total number of lead managers, total number of senior managers,
total number of managers, and total number of employees. Order your output by ascending company_code.

Note:

1.The tables may contain duplicate records.
2.The company_code is string, so the sorting should not be numeric. For example, if the company_codes are C_1, C_2, and C_10,
then the ascending company_codes will be C_1, C_10, and C_2.
Input Format

The following tables contain company data:

Company: The company_code is the code of the company and founder is the founder of the company. 

![image](https://user-images.githubusercontent.com/56919626/213913075-8d4e6f05-a4cc-4a11-a2d8-63f9282ed4f6.png)


Lead_Manager: The lead_manager_code is the code of the lead manager, and the company_code is the code of the working company. 

![image](https://user-images.githubusercontent.com/56919626/213913086-32fb7d98-3122-40a0-91d7-30e8cb317166.png)


Senior_Manager: The senior_manager_code is the code of the senior manager, the lead_manager_code is the code of its lead manager,
and the company_code is the code of the working company.

![image](https://user-images.githubusercontent.com/56919626/213913185-d3f26f51-e7ee-4cf0-afcb-48466f7d0b23.png)


Manager: The manager_code is the code of the manager, the senior_manager_code is the code of its senior manager
the lead_manager_code is the code of its lead manager, and the company_code is the code of the working company.

![image](https://user-images.githubusercontent.com/56919626/213913191-ff18abdb-0054-455b-b652-73843d7e9935.png)


Employee: The employee_code is the code of the employee, the manager_code is the code of its manager,
the senior_manager_code is the code of its senior manager, 
the lead_manager_code is the code of its lead manager, and the company_code is the code of the working company. 

![image](https://user-images.githubusercontent.com/56919626/213913209-67202d47-9272-41f6-bb0f-d977fe13ff16.png)
