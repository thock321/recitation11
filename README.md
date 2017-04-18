Recitation 11
=========

### Late Submission forms

To make the case for late submission grading easier, you will be required to fill out your details on the provided google form indicating late submission. This way, the graders will know that your latest commit needs to be pulled from the repository before grading.

The google forms for labs 3 and 4 will be out shortly and the links to the forms will be available on piazza. 

Note that you only need to fill the form if you are submitting late and not otherwise.

### Lab 2 Solutions

...

### Fork!

Consider the following program:

```
int main()
{
  int x = 1;

  if (Fork() == 0)
    printf("p1: x=%d\n", ++x);
  printf("p2: x=%d\n", --x);
  exit(0);
}
```

Now:
* What is the output of the child process?
* What is the output of the parent process?