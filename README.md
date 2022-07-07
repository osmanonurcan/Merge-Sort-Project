# Merge-Sort-Project
Patika Dev Profile: https://app.patika.dev/osmanonurcan

## Project 2
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

---

### 1. ###

    -Dizi ikiye bölünerek parçalanır.
    
      [16,21,11,8,12,22]
       /     /   \     \
    [16,21] [11] [8] [12,22]
     /   \    |    |   \   \ 
    [16] [21] [11] [8] [12] [22]
    

    
    -Parçalar sıralanıp birleştirilir.

    [16] [21] [11] [8] [12] [22]
      \    /   |    |    \  /
      [16,21] [11] [8] [12,22]
          \    /     \     /
        [11,16,21]  [8,12,22]
              \        /
          [8,11,12,16,21,22] 

---
### 2. ###

Merge sort, ikiye bölüp sıralama yaptığından,


  
    Best case    : O(n*logn)
    Average case : O(n*logn)
    Worst case   : O(n*logn) 
