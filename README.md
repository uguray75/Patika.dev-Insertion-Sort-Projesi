# Patika.dev-Insertion-Sort-Projesi
Patika.dev 'in "Veri Yapıları ve Algoritmalar" dersinin "Insertion Sort Projesi" ödevidir.

# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


# [22,27,16,2,18,6] Insertion Sort Aşamaları

[22,27,16,2,18,6]   n
[(2),27,16,22,18,6] n-1  
[(2,6),16,22,18,27] n-2
[2,6,16,22,18,27]   n-3

# [22,27,16,2,18,6] Insertion Sort Dizisi Big O Notation Gösterimi

n+(n-1)+(n-2)+(n-3)+...1 = n*(n-1) = n²+n
Baş katsayısı büyük olan Big O Notation Gösteriminde esas alınır.
O(n²)

# [22,27,16,2,18,6] Insertion Sort Dizisi sıralandıktan sonra 18 sayısı hangi case kapsamına girer

18 sayısı bu dizinin ortanca sayısıdır. Bu yüzden Average case'dir.

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

[(2),3,5,8,7,9,4,15,6]  1. aşama
[(2,3),5,8,7,9,4,15,6]  2. aşama  
[(2,3,4),8,7,9,5,15,6]  3. aşama
[(2,3,4,5),7,9,8,15,6]  4. aşama


www.patika.dev 

