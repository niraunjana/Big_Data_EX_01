# Big_Data_EX_01

# Ex:01 - Install, configure and run python, numPy and Pandas

## Aim:
To install, configure, and execute Python programs using NumPy and understand its basic functionalities like array creation, dimension handling, and indexing.

## Requirements:

1. Python installed on your system (3.x version recommended)

2. NumPy library

3. Code editor or IDE (VSCode / Jupyter / PyCharm)

4. Terminal / Command Prompt

## Algorithm:

1. Install Python and NumPy:

   - Install Python from the official website.

   - Use the command pip install numpy to install NumPy.

2. Import the NumPy library:

   - Use import numpy as np in your Python program to access NumPy functionalities.

3. Create arrays using NumPy:

   - Use the np.array() function to create 0-D, 1-D, 2-D, 3-D arrays.

   - You can pass a list or tuple as input.

4. Check the number of dimensions:

   - Use the ndim attribute to find how many dimensions an array has.

5. Access array elements using indexing:

   - Use standard indexing (arr[index]) to access elements.

## Program:

```
DEVELOPED BY : NIRAUNJANA GAYATHRI G R
REGISTER NO. : 212222230096
```
```
import numpy as np

# Step 2: Create arrays of different dimensions
arr0 = np.array(42)  # 0-D
arr1 = np.array([1, 2, 3, 4, 5])  # 1-D
arr2 = np.array([[1, 2, 3], [4, 5, 6]])  # 2-D
arr3 = np.array([[[1, 2, 3], [4, 5, 6]],
                 [[7, 8, 9], [10, 11, 12]]])  # 3-D

# Step 3: Print arrays and check their dimensions
print("0-D Array:", arr0)
print("Dimensions:", arr0.ndim)

print("1-D Array:", arr1)
print("Dimensions:", arr1.ndim)

print("2-D Array:\n", arr2)
print("Dimensions:", arr2.ndim)

print("3-D Array:\n", arr3)
print("Dimensions:", arr3.ndim)

# Step 4: Create an array with 5 dimensions
arr5 = np.array([1, 2, 3, 4], ndmin=5)
print("5-D Array:\n", arr5)
print("Number of Dimensions:", arr5.ndim)

# Step 5: Indexing array elements
print("First element of 1-D array:", arr1[0])
print("Second element of 1-D array:", arr1[1])
print("Sum of third and fourth elements:", arr1[2] + arr1[3])

# Step 6: Check numpy version
print("NumPy version:", np.__version__)

```

## Output:

![image](https://github.com/user-attachments/assets/b9a8b44b-d496-4666-b8d7-9d6183a559a7)


## Result:

NumPy was successfully installed and used to create and manipulate multi-dimensional arrays. Array operations and indexing were executed as expected.









