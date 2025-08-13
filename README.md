# Matrix Operations in C++

## Overview

This project contains a single C++ program that performs several fundamental matrix operations. These operations include matrix input/display, addition, multiplication, diagonal element summation, transpose, and comparison of rows. Matrix manipulation is a foundational topic in mathematics, computer science, and engineering disciplines.

## Matrix Operations Covered

1. Matrix Input and Display  
2. Matrix Addition  
3. Matrix Multiplication  
4. Sum of Main Diagonal Elements  
5. Transpose of a Matrix  
6. Comparison of First and Second Rows  

---

## Theory

A matrix is a two-dimensional data structure consisting of rows and columns. It is used to represent data, systems of equations, transformations, and more.

- A matrix of order m × n has m rows and n columns.
- A square matrix has the same number of rows and columns.
- The main diagonal of a matrix refers to elements where the row and column indices are the same.
- The transpose of a matrix is obtained by flipping it over its diagonal.
- Matrix addition is possible only when both matrices have the same dimensions.
- Matrix multiplication is possible only when the number of columns of the first matrix equals the number of rows of the second.

---

## Algorithm

### 1. Matrix Input and Display
- Input matrix dimensions.
- Use nested loops to read and display elements in row-wise order.

### 2. Matrix Addition
- Check if both matrices have the same dimensions.
- Add corresponding elements of both matrices and store them in a result matrix.
- Display the resulting matrix.

### 3. Matrix Multiplication
- Ensure the number of columns of the first matrix equals the number of rows of the second.
- Multiply each row element of the first matrix with each column element of the second matrix.
- Accumulate the sum of products for each position in the result matrix.
- Display the resulting matrix.

### 4. Sum of Main Diagonal Elements
- Iterate over elements where row index equals column index.
- Accumulate the sum of these diagonal elements.
- Display the sum.

### 5. Transpose of a Matrix
- Swap rows with columns.
- The element at position (i, j) in the original matrix becomes (j, i) in the transposed matrix.
- Display the transposed matrix.

### 6. Comparison of First and Second Rows
- Compare corresponding elements of the first and second rows.
- For each column, print whether the elements are equal or not.

---

## Conclusion

This C++ program demonstrates the implementation of several key matrix operations using two-dimensional arrays. Each operation introduces core programming concepts like nested loops, condition checks, and array manipulation.

By combining all operations into a single program, users can practice and understand:
- The difference between addition and multiplication of matrices.
- Validation of matrix dimensions before performing operations.
- How matrix transformations like transpose and diagonal summation work.

This project serves as a good foundation for further studies in linear algebra, numerical computing, computer graphics, and data processing.


1. Save the combined source code in a file named `matrix_operations.cpp`.
2. Compile using a C++ compiler:
