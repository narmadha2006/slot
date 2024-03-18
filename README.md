# Ex03 Time Table
## Date: 18.03.2024

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
<title>My time table</title>
</head>
<body align="center">
<img src="logo.png" height="200" width="1200" align="centre">
</center>
<table align="center" border="4" cellspacing="4" cellpadding="7" height="100" width="100">
<caption><B>SLOT TIME TABLE -NARMADHA S (23013330)</B></caption>
<tr align="center">
<th bgcolor="blue">Day/Time</th>
<th bgcolor="blue">Monday</th>
<th bgcolor="blue">Tuesday</th>
<th bgcolor="blue">Wedday</th>
<th bgcolor="blue">Thursday</th>
<th bgcolor="blue">Friday</th>
<th bgcolor="blue">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="blue">8-10</th>
<td bgcolor="pink">DE</td>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">Web</td>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">Maths</td>
</tr>
<tr>
<th bgcolor="blue">10-12</th>
<td bgcolor="pink">SE</td>
<td bgcolor="pink">Web</td>
<td bgcolor="pink">SE</td>
<td bgcolor="pink">Maths</td>
<td bgcolor="pink">Python</td>
<td bgcolor="pink">Free</td>
</tr>
<tr>
<th bgcolor="blue">12-1</th>
<td colspan="6" align="center" bgcolor="cyan">LUNCH</td>
</tr>
<tr>
<th bgcolor="blue">1-3</th>
<td bgcolor="pink">Web</td>
<td bgcolor="pink">Physics</td>
<td bgcolor="pink">Physics</td>
<td bgcolor="pink">EDM</td>
<td bgcolor="pink">DE</td>
<td bgcolor="pink">Free</td>
</tr>
<tr>
<th bgcolor="blue">3-5</th>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">EDM</td>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">Python</td>
<td bgcolor="pink">Free</td>
<td bgcolor="pink">Free</td>
</tr>
</table>
    </body>
<body>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI301</td>
<td>Python Programming(Python)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI302</td>
<td>Engineering Design and Modelling(EDM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>Fundamentals of web Application and Development(Web)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS408</td>
<td>Software Engineering(SE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EE404</td>
<td>Digital Electronics(DE)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models(Maths)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19PH214</td>
<td>Physics for Quantum Computing(Physics)</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-03-18 223608.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
