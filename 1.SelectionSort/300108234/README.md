#Hali
def selectionsort(arr):
  newArr = []
  for i in range(len(arr)):
      smallest = findSmallest(arr)
      newArr.append(arr.pop(smallest))
  return newArr 

print selectionsort([5, 3, 6, 2, 10])
