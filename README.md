# Insertion-Sort-Projesi


[Patika.dev](https://www.patika.dev/tr)


## [22,27,16,2,18,6] __>Insertion Sort

## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
     - [22,27,16,2,18,6]    n
     - [2,27,16,22,18,6]    n-1
     - [2,6,16,22,18,27]    n-2
     - [2,6,16,18,22,27]    1 
     
## 2.Big-O gösterimini yazınız.    
     - (n.(n+1))/2
     - (n^2+n)/2
     - O(n^2)
    
## 3.Time Complexity: 
     - Average case: Aradığımız sayının(18) ortada olması -->[2,6,16,18,22,27]
     - Worst case: Aradığımız sayının(2) sonda olması,   -->[27,22,18,16,6,2]
     - Best case: Aradığımız sayının(2) dizinin en başında olması. -->[2,6,16,18,22,27]
     
## 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
     - [2,6,16,18,22,27] Dizinin sıralanmış hali
     - Aradığımız sayı dizinin ortasında bulunduğu için Average case kapsamına girer.
   
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
     -[7,3,5,8,2,9,4,15,6]    n
     -[2,7,5,8,3,9,4,15,6]    n-1
     -[2,3,5,8,7,9,4,15,6]    n-2
     -[2,3,4,8,7,9,5,15,6]    n-3
     

