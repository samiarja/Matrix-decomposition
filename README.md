# Matrix-decomposition
<br>

A Matrix decomposition is a way of reducing matrix into constituent parts.
<br>

**What is that mean?**
<br>

It is an approach that can simplify more complex matrix operations that can be performed on the decomposed matrix rather than on the original one itself.
<br>

**Matrix decomposition types:**
<br>

* LU Matrix Decomposition
* QR Matrix Decomposition
* Cholesky Decomposition

### What is LU Decomposition?
<br>

The LU decomposition is for square matrices and decomposes a matrix into L and U components.

A= L . U

Where A is the square matrix that we wish to decompose, L is the lower triangle matrix and U is the upper triangle matrix.

> The factors L and U are triangular matrices. The factorization that comes from elimination is A = LU.
<br>

**It looks like this:**
<br>

![LU Decomposition](https://github.com/samiarja/Matrix-decomposition/blob/master/lu-decomp.PNG)

The LU decomposition is often used to simplify the solving of systems of linear equations, such as finding the coefficients in a linear regression, as well as in calculating the determinant and inverse of a matrix.
<br>

### What is QR Decomposition?
<br>

The QR decomposition is for m x n matrices and decomposes a matrix into Q and R components.
Is decomposition of a matrix into an orthogonal matrix multipled by an upper-triangular matrix. It looks like this
![Qr Decomposition](https://github.com/samiarja/Matrix-decomposition/blob/master/qr-decomp.PNG)
<br>

Where A is the matrix that we wish to decompose, Q a matrix with the size m x n, and R is an upper triangle matrix with the size m x n.
<br>



