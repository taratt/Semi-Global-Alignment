# Semi-Global-Alignment
This project is an implementation of semi-global alignment for proteins using dynamic programming. In this implementation PAM250 matrix is used tto score matches and mismatches and gap penalty is considered to be 9.
## Input
The inputs to this code are two strings representing two molecules of protein that are going to be semi-globally aligned to one another.
Example:
```
AAAAA
AA
```
## Output
The outputs of this code are the alignment score which is printed to the first line of the output and the next following lines which are all of the possible ways that the alignment of the two proteins can be done.
<br>
Example:
```
4
AAAAA
---AA
AAAAA
--AA-
AAAAA
-AA--
AAAAA
AA---
```
