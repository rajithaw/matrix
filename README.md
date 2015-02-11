## Matrix

A general purpose matrix class which can be used for easily performing matrix manupilation functions like Multiplication, Division, Addition, Substraction and finding Inverse, Determinant, Transpose etc.

####Usage

**_Construction_**

```c#
Matrix result = new Matrix(3, 3);
```

**_Equality_**

```c#
bool result = matrix1 == matrix2;
```

**_Inequality_**

```c#
bool result = matrix1 != matrix2;
```

**_Addition_**

```c#
Matrix result = matrix1 + matrix2;
```

**_Substraction_**

```c#
Matrix result = matrix1 - matrix2;
```

**_Multiplication_**

```c#
Matrix result1 = matrix1 * matrix2;
Matrix result2 = matrix1 * 3;
```

**_Division_**

```c#
Matrix result = matrix1 / 3;
```

**_Transpose_**

```c#
Matrix result = ~matrix1;
```

**_Inverse_**

```c#
Matrix result = !matrix1;
```

**_Power_**

```c#
Matrix result = matrix1 ^ 3;
```

**_Determinant_**

```c#
float det = matrix1.Determinant();
```

**_Adjoint_**

```c#
Matrix adj = matrix1.Adjoint();
```

**_Minor_**

```c#
Matrix min = matrix1.Minor(1, 1);
```
