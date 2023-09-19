# pandas-challenge

## PyCitySchools
The PyCitySchools folder contains the files needed to analyze student and school data, which can be found in the respective files student_complete.csv and schools_complete.csv in the Resources folder. 

The student_complete.csv has 7 columns of data: _Student ID_, _student_name_, _gender_, _grade_, _school_name_, _reading_score_, and _math_score_. The schools_complete.csv has 5 columns of data: _School_, _ID_, _school_name_, _type_, _size_, and _budget_.

The PyCitySchools folder also contains the PyCitySchools.ipynb script which is the Jupyter Notebook script, that when runs analyzes the data within student_complete.csv and schools_complete.csv files.

The PyCitySchools.ipynb outputs two summaries and sorts the data 7 different ways.

The first summary is the District summary which includes
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

The second summary is the School summary which includes
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

The script also sorts the data in the following ways:
- Highest-Performing Schools (by % Overall Passing)
- Lowest-Performing Schools (by % Overall Passing)
- Math Scores by Grades
- Reading Scores by Grades
- Scores by School Spending
- Scores by School Size
- Scores by School Type

## Citations
The script in PyCitySchools.ipynb contains code from the following website:
- https://saturncloud.io/blog/how-to-get-the-first-row-of-each-group-in-a-pandas-dataframe/
  The code from this website was used to grab the first row in each group of the dataFrame. It is present in codebox [6].
- the script also contains code from starting code that was given with the intial assignment as a template/format, that file was called PyCitySchools_starter.ipynb.
