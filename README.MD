# JS Problem Solvings For Coding Interview

# JavaScript Coding Interview Problems

This document provides a list of JavaScript coding interview problems to help you practice and prepare for technical interviews. Each problem is designed to test your understanding of fundamental programming concepts and problem-solving skills.

## Problem List

### 1. Reverse a String

**Description**: Write a function that takes a string as input and returns the string reversed.

**Example**:

```jsx
reverseString("hello"); // Output: "olleh"
```

**Requirements**:

- The function should handle empty strings.
- The function should work with strings containing special characters and numbers.

---

### 2. Count Vowels in a String

**Description**: Write a function to count the number of vowels (a, e, i, o, u) in a given string.

**Example**:

```jsx
countVowels("hello world"); // Output: 3
```

**Requirements**:

- The function should be case-insensitive.
- The function should handle strings with no vowels.

---

### 3. Capitalize the First Character of Each Word

**Description**: Write a function that capitalizes the first character of each word in a string.

**Example**:

```jsx
capitalizeWords("hello world"); // Output: "Hello World"
```

**Requirements**:

- The function should handle multiple spaces between words.
- The function should handle empty strings.

---

### 4. Sum of Digits of a Number

**Description**: Write a function that finds the sum of the digits of a given number.

**Example**:

```jsx
sumOfDigits(1234); // Output: 10 (1 + 2 + 3 + 4)
```

**Requirements**:

- The function should handle positive integers.
- The function should handle numbers with multiple digits.

---

### 5. Find the Largest Number in an Array

**Description**: Write a function that takes an array of numbers and returns the largest number in the array.

**Example**:

```jsx
findLargest([1, 5, 3, 9, 2]); // Output: 9
```

**Requirements**:

- The function should handle arrays with a single number.
- The function should handle arrays with negative numbers.

---

### 6. Remove Duplicates from an Array

**Description**: Write a function that takes an array and returns a new array with all duplicates removed.

**Example**:

```jsx
removeDuplicates([1, 2, 2, 3, 4, 4, 5]); // Output: [1, 2, 3, 4, 5]
```

**Requirements**:

- The function should handle arrays with all unique elements.
- The function should work with arrays containing different types of duplicates.

---

### 7. Find the Second Largest Number in an Array

**Description**: Write a function that takes an array and returns the second largest number in the array.

**Example**:

```jsx
findSecondLargest([1, 5, 2, 3, 4]); // Output: 4
```

**Requirements**:

- The function should handle arrays with less than two distinct numbers.
- The function should work with arrays containing duplicate numbers.

---

### 8. Flatten a Nested Array

**Description**: Write a function that takes a nested array and returns a new array with all sub-array elements concatenated into it recursively.

**Example**:

```jsx
flattenArray([1, [2, [3, 4], 5]]); // Output: [1, 2, 3, 4, 5]
```

**Requirements**:

- The function should handle arrays with various levels of nesting.
- The function should handle arrays with mixed types of elements.

---

### 9. Rotate an Array

**Description**: Write a function that rotates an array `k` times. Each rotation moves the last element of the array to the front.

**Example**:

```jsx
rotateArray([1, 2, 3, 4, 5], 2); // Output: [4, 5, 1, 2, 3]
```

**Requirements**:

- The function should handle cases where `k` is greater than the length of the array.
- The function should handle empty arrays.
