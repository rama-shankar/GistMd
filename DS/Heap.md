# satisfy a heap property
## max-heap
 the max-heap property is that for every node i other than the root , 
 PARENT(i) >= A[i];
## min-heap 
 is organized in the opposite way; the min-heap property is that for every node i other than the root,
 PARENT(i) <= A[i];
```
A = [16, 14, 10, 8, 7, 9, 3, 2, 4, 1];

PARENT(i){
  return A[i/2];
}

LEFT(i){
  return A[2*i]
}

RIGHT(i){
  return A[2*i +1]
}

2i == i << 1;
2i+1 == i << 1; + 1;
i/2 == i >> 1;
```
