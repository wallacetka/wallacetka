- 👋 Hi, I’m @wallacetka
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
package com.example;

import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        // Demonstration of Arrays
        // Arrays have a fixed size, defined at the time of creation.
        int[] array = new int[5];
        array[0] = 1;
        array[1] = 2;
        array[2] = 3;
        array[3] = 4;
        array[4] = 5;

        // Accessing elements in an array
        System.out.println("Array elements:");
        for (int i = 0; i < array.length; i++) {
            System.out.println("Element at index " + i + ": " + array[i]);
        }

        // Demonstration of ArrayList
        // ArrayLists can dynamically change size, meaning elements can be added or removed.
        ArrayList<Integer> arrayList = new ArrayList<>();
        arrayList.add(1);
        arrayList.add(2);
        arrayList.add(3);
        arrayList.add(4);
        arrayList.add(5);

        // Accessing elements in an ArrayList
        System.out.println("ArrayList elements:");
        for (int i = 0; i < arrayList.size(); i++) {
            System.out.println("Element at index " + i + ": " + arrayList.get(i));
        }

        // Adding an element to the ArrayList
        arrayList.add(6);
        System.out.println("ArrayList after adding an element:");
        for (int i = 0; i < arrayList.size(); i++) {
            System.out.println("Element at index " + i + ": " + arrayList.get(i));
        }

        // Removing an element from the ArrayList
        arrayList.remove(2); // Removes the element at index 2
        System.out.println("ArrayList after removing an element:");
        for (int i = 0; i < arrayList.size(); i++) {
            System.out.println("Element at index " + i + ": " + arrayList.get(i));
        }

        // Summary of differences:
        // 1. Arrays have a fixed size, while ArrayLists can dynamically resize.
        // 2. Arrays can store primitive types and objects, whereas ArrayLists can only store objects.
        // 3. Arrays provide faster access to elements due to contiguous memory allocation, but lack flexibility.
        // 4. ArrayLists provide methods for easy data manipulation such as add, remove, and contains.
    }
}
<!---
wallacetka/wallacetka is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Explanation and Comments:

    Array Initialization:
        Arrays require a fixed size upon creation.
        The code correctly initializes the array with five elements and assigns values to each index.

    Array Access:
        The for loop iterates through the array using the array.length property to access and print each element.

    ArrayList Initialization:
        The ArrayList is correctly initialized without a fixed size.
        Elements are added dynamically using the add method.

    ArrayList Access:
        The for loop iterates through the ArrayList using the size method to access and print each element.

    Adding and Removing Elements in ArrayList:
        Elements are added and removed dynamically from the ArrayList using the add and remove methods.

Summary of Key Points:

    Fixed Size vs. Dynamic Size:
        Arrays have a fixed size, whereas ArrayLists can resize dynamically.
    Data Type Storage:
        Arrays can store both primitives and objects, while ArrayLists store objects and use wrapper classes for primitives.
    Memory Allocation:
        Arrays allocate memory contiguously for all elements, providing faster access.
        ArrayLists allocate memory dynamically, which may involve resizing.
    Methods for Manipulation:
        Arrays offer basic operations with limited methods.
        ArrayLists provide rich methods for easy manipulation of data.

This code is now syntactically and logically correct. Running it in your IDE will demonstrate the differences between arrays and ArrayLists as intended.
