# Your-Sorting-and-Searching-Algorithm

def reading_sort(array1, max_val):
    dave = max_val + 1
    count = [0] * dave

    for ainz in array1:
        #count occures
        count [ainz] += 1
    i = 0
    for ainz in range(dave):
        for l in range (count[ainz]):
            array1[i] = ainz
            i += 1
    return array1

print (reading_sort( [1,3,9,5,3,1,4,3,5,3,9,1,2,6,6,3,6],4))
