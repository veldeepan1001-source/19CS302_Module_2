# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:29/04/2025
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start.
2. Define a variables n,digit,sum.
3. Read the value using scanf.
4. Ask the user to make an input
5. Print out the answer
6. End.

## Program:
```
#include <stdio.h>
int main() {
    int n, digit, sum = 0;
    scanf("%d", &num);
    if (n < 0) {
        n = -num;
    }
    do {
        digit = n % 10; 
        if (digit % 2 != 0) { 
            sum += digit;
        }
        n /= 10; 
    } while (n > 0);
    printf("Sum of odd digits: %d\n", sum);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/2841145c-c816-44e2-a4a6-8b567b10d0a6)

## Result:
Thus the program was executed and the output was verified successfully.
