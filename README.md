Sorting Algorithms in Java assignment in  RANDOM GENERATED ARRAY

This Java program implements five different sorting algorithms:

Bubble Sort

Selection Sort

Insertion Sort

Quick Sort

Merge Sort

It then applies one of these algorithms to sort a large dataset and measure the execution time.

How to Use

Compile the program:

javac SortingAlgorithms.java

Run the program:

java SortingAlgorithms

Modifying the Sorting Algorithm

By default, the program uses Quick Sort, as it is efficient for large datasets. If you want to use another algorithm:

Comment out the current sorting algorithm in the main method.

Uncomment the desired sorting algorithm.

Example:

// bubbleSort(testArray);    // Too slow for large input
// selectionSort(testArray); // Too slow for large input
// insertionSort(testArray); // Too slow for large input
quickSort(testArray, 0, testArray.length - 1); // Fast for large input
// mergeSort(testArray, 0, testArray.length - 1); // Fast for large input

For small datasets, Bubble Sort, Selection Sort, or Insertion Sort might be suitable, but they are inefficient for large datasets.

Performance Considerations

Bubble Sort, Selection Sort, and Insertion Sort are O(n²) and are slow for large inputs.

Quick Sort and Merge Sort are O(n log n) and much faster for large inputs.

Example Output

Sorting completed in 35ms
First 10 sorted numbers: [1, 2, 5, 8, 10, 15, 20, 22, 25, 30]

Notes

The program generates an array of 1,000,000 random numbers between 1 and 1000.

Modify the size variable to test different input sizes.

Ensure you allocate enough memory if handling very large datasets.

Enjoy experimenting with different sorting algorithms!

