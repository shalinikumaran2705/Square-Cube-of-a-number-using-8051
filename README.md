# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END
```

## OUTPUT

<img width="957" height="205" alt="image" src="https://github.com/user-attachments/assets/cecb623a-5b2c-417e-9c6e-d0c93e1a07a1" />

## CALCULATION

![WhatsApp Image 2026-02-18 at 11 07 00 AM](https://github.com/user-attachments/assets/055c6a10-3fc1-456e-9523-e170f9c761af)


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A,P0
MOV B,A
MUL AB
MOV R0,A
MOV B,P0
MUL AB
MOV P2,A
END
```


## OUTPUT

<img width="445" height="312" alt="image" src="https://github.com/user-attachments/assets/1fa31ff2-207f-4b38-8c15-cbf495bd9aec" />

## CALCULATION

<img width="1512" height="1600" alt="image" src="https://github.com/user-attachments/assets/f3b615de-3d00-466a-9e34-b86334301463" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


