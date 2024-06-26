# Ex03 Time Table
## Date : 22/03/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
### HTML 
```html
<html>
    <head>
        <title>
            MY SLOT
        </title>
        <link rel="stylesheet" href="san.css">
    </head>
    <body class="bg">
        <center>
            <img src="logo.png" with="100px", height="100px"><br><br><br>
            <h2 class="name">SLOT TIME TABLE SANJAY S (212221243002)</h2>
            <table border="6" class="table1">
                <tr class="dt">
                    <th>Day/Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thuresday</th>
                    <th>Friday</th>
                </tr>
                <tr>
                    <td class="dt">8-10</td>
                    <td>FUN WEB</td>
                    <td class="fs">FREE SLOT</td>
                    <td>ADVANCE C</td>
                    <td class="fs">FREE SLOT</td>
                    <td>PS</td>
                </tr>
                <tr>
                    <td class="dt">10-12</td>
                    <td class="fs">FREE SLOT</td>
                    <td>DIP</td>
                    <td>DIP</td>
                    <td>C# AR VR</td>
                    <td>SOFT</td>
                </tr>
                <tr>
                    <td class="dt">12-01</td>
                    <td colspan="5" style="text-align: center; color: rgb(12, 131, 12)">LUNCH BREAK</td>
                </tr>
                <tr>
                    <td class="dt">01-03</td>
                    <td>C# & AR VR</td>
                    <td>SOFT</td>
                    <td class="fs">FREE SLOT</td>
                    <td>FUN WEB</td>
                    <td>FUN WEB</td>
                </tr>
                <tr>
                    <td class="dt">03-05</td>
                    <td class="fs">FREE SLOT</td>
                    <td class="fs">FREE SLOT</td>
                    <td>PS</td>
                    <td class="fs">FREE SLOT</td>
                    <td class="fs">FREE SLOT</td>
                </tr>
            </table>
            <br> <br> 
            <table border="6" class="table2">
                <tr>
                    <th>S. No.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI414</td>
                    <td><b>Fundamental of Web Application Development [FUN WEB]</b></td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19AI308C</td>
                    <td><b>C Sharp and Virtual Reality [C# AR VR]</b></td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19AI406</td>
                    <td><b>Digital Image Processing Techniques [DIP]</b></td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19CS408</td>
                    <td><b>Software Engineering [SOFT]</b></td>
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19EN105</td>
                    <td><b>Public Speaking [PS]</b></td>
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19AI305</td>
                    <td><b>Advance C programming [ADVANCE C]</b></td>
                </tr>
            </table>
        </center>
    </body>
</html>
```
### EXTERNAL CSS 
```css
.name{
    font-family: 'Times New Roman', Times, serif;
}
.bg{
    background-color: rgb(222, 217, 187);
}
.table1{
    background-color: rgb(250, 235, 215);
}
.table2{
    background-color: rgb(213, 202, 228);
}    
.dt{
    background-color: rgb(166, 224, 232);
}
.fs{
    color: coral;
}
b{ 
    color:rgb(36, 99, 105); 
}
```

## OUTPUT
![alt text](<Screenshot (11).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
