# Ex04 Time Table
## Date: 21-11-26

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```<html>
    <head>
        <title>assignment</title>
    </head>
    <body>
        <h2>nethajisamaranj26015547</h2>
        <img src="logo.png" alt="error on img" height="12%" width="60%">
        
        <table bgcolor="grey" border="5px" align="center">
            <caption align="center" >SLOT TIMETABLE _NETHAJISAMARANJ</caption>
            <tr bgcolor="lightblue">
                <th>Day/Time</th>
                <th>MON</th>
                <th>TUE</th>
                <th>WED</th>
                <th>THU</th>
                <th>FRI</th>
            </tr>
            <tr>
                <th bgcolor="lightblue">8-10</th>
                <td>py</td>
                <td>math</td>
                <td>edm</td>
                <td>web</td>
                <td>meet</td>

            </tr>
            <tr>
                <th bgcolor="lightblue">10-12</th>
                <td>ger</td>
                <td>fwad</td>
                <td>py</td>
                <td>ce</td>
                <td>edm</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">12-1</th>
                <td colspan="5" >LUNCH</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">1-3</th>
                <td colspan="2">FREE</td>
                <td>mat</td>
                <td>mat</td>
                <td>ss</td>

            </tr>
            <tr>
                <th bgcolor="lightblue">3-5</th>
                <td colspan="2">FREE </td>
                <td>ger</td>
                <td>che</td>
                <td>fwad</td>
            </tr>
        </table>
        <table  border="5px" align="center" >
            <tr>
                <th>S.NO</th>
                <td>Subject Code</td>
                <td>Subject name</td>
            </tr>
             <tr>
                <th>1</th>
                <td>19al143</td>
                <td>fwad</td>
            </tr>
            <tr>
                <th>2</th>
                <td>19al145</td>
                <td>EDM</td>
            </tr>
              <tr>
                <th>3</th>
                <td>19al145</td>
                <td>MATH</td>
            </tr>
             <tr>
                <th>4</th>
                <td>19al145</td>
                <td>GERMANY</td>
            </tr>
             <tr>
                <th>5</th>
                <td>19al154</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>


     

        </table>


    </body>
</html>
```

## OUTPUT
webpage
![webpage](<Screenshot 2026-11-21 122118.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
