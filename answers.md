Answers to SQL Queries Qeustions:


1. Select all rows from the classes table.

school=# SELECT * FROM classes;
 id |   name   | credits 
----+----------+---------
  1 | CS 101   |       4
  2 | HIST 107 |       3
  3 | SPAN 210 |       3
  4 | PHYS 218 |       4
  5 | ART 118  |       2
(5 rows)



2. Select the name and credits from the classes table where the number of credits is greater than 3.

school=# SELECT name, credits FROM classes WHERE credits > 3;
   name   | credits 
----------+---------
 CS 101   |       4
 PHYS 218 |       4
(2 rows)



3. All rows from the classes table where credits is an even number.

school=# SELECT * FROM classes WHERE credits % 2 = 0;
 id |   name   | credits 
----+----------+---------
  1 | CS 101   |       4
  4 | PHYS 218 |       4
  5 | ART 118  |       2
(3 rows)


4. All of Tianna's enrollments that she hasn't yet received a grade for.


5. All of Tianna's enrollments that she hasn't yet received a grade for, selected by her first name, not her student.id

6. All of Tianna's enrollments that she hasn't yet received a grade for, selected by her first name, not her student.id, with the class name included in the result set.

7. All students born before 1986 who have a 't' in their first or last name.

8. The average age of all the students.

9. Addresses that have a space in their city name.

10. Students & their addresses that live in a city with more than one word in the city name.

11. The average number of credits for classes offered at the school.

12. The first and last name of all students who have received an 'A'.

13. Each student's first name and the total credits they've enrolled in

14. The total number of credits each student has received a grade for.

15. All enrollments, including the class name.

16. Students born between 1982-1985 (inclusive).

17. Insert a new enrollment recording that Andre Rohan took PHYS 218 and got an A.