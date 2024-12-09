# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html>
    <center>
        <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-11-21 143721.png">
    </center>
    <head>
        <title>Time Table 📆</title>
        <style>
            table,th,td{
                text-align: center;
                border: 4px ;
            }
        </style>
    </head>
    <body>
        <center>
            <h2 style="text-align: center;"> TIME TABLE- Sai Deshiya</h2>
            <table style="background-color:rgb(228, 119, 163)">
                <th>DAYS</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color:rgb(228, 119, 163) ">MONDAY</th>
                <td>Digital Electronics</td>
                <td>Web application</td>
                <td rowspan="7">L<br>U<br>N<br>C<br>H<BR>~</td>
                <td>Python</td>
                <td>-</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(228, 119, 163)">TUESDAY</th>
                <td>Edm</td>
                <td>Digital Electronics</td>
                <td>Python</td>
                
                <td>-</td>
                
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(228, 119, 163)">WEDNESDAY</th>
                <td></td>
                <td>English</td>
                <td>Mentor Meeting</td>
                <td>-</td>
                
                
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(228, 119, 163)">THURSDAY</th>
                <td>-</td>
                <td>-</td>
                
                <td>Web application</td>
                <td>-</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(228, 119, 163)">FRIDAY</th>
                <td>Calcus and Matrix</td>
                <td>Python</td>
                
                <td>Edm</td>
                <td>-</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(228, 119, 163)">SATURDAY</th>
                <td>English</td>
                <td>Calcus and Matrix</td>
                
                <td>-</td>
                <td>Web application</td>
            </tr>
           
            
        </table>
        </center>
    </body>
</html>
 <br>
 <br>
 <center>
    <table bgcolor="lavender">
        <tr bgcolor="plum">
            <th>S.no</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td bgcolor="plum">1.</td>
            <td bgcolor="plum">19MA201</td>
            <td bgcolor="plum">Calculus and Matrix Algebra</td>
            
        </tr>
        <tr>
<td bgcolor="plum">2.</td>
            <td bgcolor="plum">19AI301</td>
            <td bgcolor="plum">Python Programming</td>
        </tr>
        <tr>
            <td bgcolor="plum">3.</td>
            <td bgcolor="plum">19EE404</td>
            <td bgcolor="plum">Digital Electronics </td>
        </tr>
        <tr>
        <td bgcolor='plum'>4.</td>
            <td bgcolor="plum">19AI414</td>
            <td bgcolor="plum">Fundamental od Web Application Development</td>
        </tr>
        <tr>
        <td bgcolor="plum">5.</td>
            <td bgcolor="plum">19AI302</td>
            <td bgcolor="plum">Engineering Design and Modeling</td>
        </tr>
        <tr>
        <td bgcolor="plum">6.</td>
            <td bgcolor="plum">ECA-M-SCOFT</td>
            <td bgcolor="plum">Mentor Meet</td>
        </tr>
    </table>
 </center>
```
# OUTPUT
![Screenshot (82)](https://github.com/user-attachments/assets/b8eb7d7b-0ede-4696-879e-75b26ea8894e)



# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
