# Ex03 Time Table
## Date:14-03-2024

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
```
<html>
<head>
<title> Sample Super  Web</title>
</head>
<body>
<img src="logo.png" height="200" width="1200">
<table border ="2" cellpadding="2" width="400" heigth="400" bgcolor="yellow">
<caption> <h2>Camu Schedule -V.Natchathira Rajan(212221040112)</h2></caption>
<tr bgcolor="green">
<th>Date</th>
<th>MONDAY</th>
<th>TUESDAY</th>
<th>WEDNESDAY</th>
<th>THURSDAY</th>
<th>FRIDAY</th>
<th>SATURDAY</th>
</tr>
<tr>
<td bgcolor="green">8-10</td>
<td>Free</td>
<td>AI</td>
<td>TOC</td>
<td rowspan="2">FREE</td>
<td>FWAT</td>
<td>MPMC</td>
</tr>
<tr>
<td bgcolor="green">10-12</td>
<td>MPMC</td>
<td>Ind Ast</td>
<td>BEEE</td>
<td>FREE</td>
<td>TOC</td>
</tr>
<tr bgcolor="#008000">
<td>12-1</td>
<td colspan="6" align="center"> LUNCH BREAK</td>
</tr>
<tr>
<td bgcolor="green">1-3</td>
<td>BEEE</td>
<td>FWAT</td>
<td>MPMC</td>
<td>FWAD</td>
<td rowspan="2" align="center"> FREE</td>
<td>CAD</td>
</tr>
<tr>
<td bgcolor="green">3-5</td>
<td colspan="3" align="center"> FREE</td>
<td>CAD</td>
<td>AI</td>
</tr>
</table>
<space>"      " </space>
<table border ="2" cellpadding="2" width="400" heigth="400" bgcolor="pink">
<tr bgcolor="brown ">
<th>S.no</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19CS413</td>
<td>Artifical Intelligence</td>
</tr>
<tr>
<td>2</td>
<td>19CS407</td>
<td>Theory of Compution</td>
</tr>
<tr>
<td>3</td>
<td>19AI414</td>
<td>Fundamental Of web Development</td>
</tr>
<tr>
<td>4</td>
<td>19ME505</td>
<td>Computer Aided Design</td>
</tr>
<tr>
<td>5</td>
<td>19EE305</td>
<td>Basic Electonic and Measurement Engineering</td></tr>
<tr>
<td>6</td>
<td>19EC408</td>
<td>Microprocessor and Microcontroller</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](<slot output.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
