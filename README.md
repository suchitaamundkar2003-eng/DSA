Radix sort is a **non-comparative sorting algorithm** that sorts numbers (or strings) by processing individual digits or characters from the **least significant position to the most significant** (LSD Radix Sort) or vice versa (MSD Radix Sort).

It works by grouping items into “buckets” based on each digit’s value and repeatedly reorganizing the list digit by digit. Since it uses counting/bucket sort for each digit, its time complexity is typically **O(d·(n + k))**, where *d* is the number of digits and *k* is the range of each digit.

Radix sort is efficient for large datasets with fixed-length keys and is often faster than comparison-based sorts when conditions are favorable.
