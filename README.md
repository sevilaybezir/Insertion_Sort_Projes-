# Insertion Sort Projesi 
## Proje 1
#### [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

En baştan sayılara bakmaya başlanır ve en küçüğünü bulunca birinci adımdaki ile yer değiştirilir. Bu işlem kendisinden sonraki her eleman için uygulanır. Buna göre;

* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

1'den n'e kadar olan sayıların toplamını içerir. 
 n(n+1)/2=n²n/2
Baskın olan alınır. Yani Big-O gösterimi;
O(n²)

3. Time Complexity: 
- Average case: Aradığımız sayının ortada olması,
  * Big-O: O(n²)
- Worst case: Aradığımız sayının sonda olması,
  * Big-O: O(n²)
- Best case: Aradığımız sayının dizinin en başında olması.
   * Big-O: O(n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   - Aradığımız sayı ortada olduğu için,
   Average case: 


5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]

