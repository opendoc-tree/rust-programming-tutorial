# Data Types
Rust is a **statically typed language**. Rust data types are divided into two main groups: 
1) scalar
2) compound

## Scalar
Scalar = single value  
In rust scalar type represnt single value. Rust has four scalar type: 
1) Integer
2) Floating-point
3) Boolean
4) Character

### Integer
An integer is a number without a fractional part. Integer has two types:
#### 1) Signed
Represent both positive and negative numbers
Length|Types
-|-
8-bit|i8
16-bit|i16
32-bit|i32
64-bit|i64
128-bit|i128
Depend on the architecture |isize
**isize** depend on the architecture of the computer where your program is running. It will be 64-bits if you’re on a 64-bit architecture and will be 32-bits if you’re on a 32-bit architecture

**Formula to calculate the range of a signed integer**  
$$\text{ from } -2^{n-1} \text{ to } 2^{n-1} - 1$$
**n** is the number of bits. So, an **i8** can store from -128 to 127
$$\text{ from }-2^{8-1} = -2^7 = -128\text{ to }2^{8-1} - 1 = 2^7 - 1 = 128 - 1 = 127$$
#### 2) Unsigned
Represent only non-negative numbers (0 and positive)
Length|Types
-|-
8-bit|u8
16-bit|u16
32-bit|u32
64-bit|u64
128-bit|u128
Depend on the architecture |usize
**usize** depend on the architecture of the computer where your program is running. It will be 64-bits if you’re on a 64-bit architecture and will be 32-bits if you’re on a 32-bit architecture

**Formula to calculate the range of a unsigned integer**  
$$\text{ from } 0 \text{ to } 2^n - 1$$
**n** is the number of bits. So, an **u8** can store from 0 to 255
$$2^8 - 1 = 256 - 1 = 255$$


