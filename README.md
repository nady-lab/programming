# programming (CMPU1025)

all my lab work from first-year programming at TU Dublin, written in C. it starts with printing my first variables and ends with reading and comparing text files, so you can follow the whole course in order by going through the folders.

## running a lab

each question is a single file, so there's nothing to set up beyond having `gcc`:

```bash
gcc Lab5/Lab5Q1.c -o lab5q1
./lab5q1            # on windows: lab5q1.exe
```

compiled `.exe` files are gitignored, so they won't clutter the repo.

## what each lab covers

| labs | topic |
|------|-------|
| 1 | first programs, input and output, finding and fixing errors |
| 2 to 3 | variables, arithmetic, the modulus operator, formulas like volume and surface area, reading numbers from the keyboard |
| 4 | reading a character, checking a number is in range, making decisions |
| 5 | loops (counting up and down, even and odd numbers, sums) |
| 6 | 1-D arrays |
| 7 to 8 | 2-D arrays |
| 9 to 10 | pointers, pointer notation, walking through arrays with pointers |
| 11 to 13 | functions, return values, pass by value, pass by reference, passing arrays |
| 14 to 16 | strings and character arrays |
| 17 to 18 | structs |
| 19 to 20 | file input and output (comparing two text files, numbering lines, timing `fgetc()` against `fgets()` on a large file) |

## folders

```
Lab1 ... Lab20/       one folder per lab, one file per question (Lab5Q3.c is lab 5, question 3)
ProgrammingLabTest/    labtest1.c and labtest2.c
```

some labs include the text files their programs read (`Lab19` and `Lab20`), so run those from inside their folder.
