# 2019-tasks

## 1. Century From Year
The first century spans from the year 1 up to and including the year 100, The second - from the year 101 up to and including the year 200, etc.

Examples:
centuryFromYear(1705)  returns (18)
centuryFromYear(1900)  returns (19)
centuryFromYear(1601)  returns (17)
centuryFromYear(2000)  returns (20)

## 2. validate PIN code
ATM machines allow 4 or 6 digit PIN codes and PIN codes cannot contain anything but exactly 4 digits or exactly 6 digits.

validate_pin("1234") == True
validate_pin("12345") == False
validate_pin("a234") == False

## 3. Triangle
Given the triangle of consecutive odd numbers:

             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29

row_sum_odd_numbers(1); # 1
row_sum_odd_numbers(2); # 3 + 5 = 8


## 4. Descending Order
Your task is to make a function that can take any non-negative integer as a argument and return it with its digits in descending order. Essentially, rearrange the digits to create the highest possible number.

Examples:
Input: 21445 Output: 54421
Input: 145263 Output: 654321
Input: 1254859723 Output: 9875543221

## 5. Flatten and sort an array
Given a two-dimensional array of integers, return the flattened version of the array with all the integers in the sorted (ascending) order.

Example:
Given [[3, 2, 1], [4, 6, 5], [], [9, 7, 8]], your function should return [1, 2, 3, 4, 5, 6, 7, 8, 9].
