def bubble_sort(a):
    # Implement code to bubble sort the given array a in place.
    # Also return the number of comparisons. 
    # Num of comparisons is initialized to 0
    num_compares = 0
    n = len(a)
    # run loop from index 0 to n-1
    for i in range(n-1):
        # run loop from 0 to what needs to be sorted 
        for j in range(n-1-i):
            # increment num_compares
            num_compares = num_compares + 1
            # if left element is greater than right element, swap 
            if a[j] > a[j+1]:
                a[j], a[j+1] = a[j+1], a[j]
    return num_compares
    
# TESTING CODE
a = [3, 10, 1, 29, -1, 4, 3, 15, 2, -2]
nc = bubble_sort(a)
print('Num Comparison = ', nc)
print('Sorted Result = ', a)
