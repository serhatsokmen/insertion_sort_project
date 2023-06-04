# insertion_sort_project

## SORU 1:
[22,27,16,2,18,6] -> insertion sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

## CEVAP 1:
Dizi n,n-1,n-2,....,1 şeklinde devam eder. Dizinin bize verilen hali n halidir. Direkt (n-1). adımdan başlayalım.
Adım (n-1) = [2,22,27,16,18,6] 
Adım (n-2) = [2,6,22,27,16,18] 
Adım (n-3) = [2,6,16,22,27,18] 
Adım 1 = [2,6,16,18,22,27] 

## SORU 2:
Big-O gösterimini yazınız.

## CEVAP 2:
n(n+1)/2 == (n^2+n)/2 == n^2
Big-O gösterimi : n^2

## SORU 3:
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
1. Avarege case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması

## CEVAP 3:
Dizimizin sıralanmış hali = [2,6,16,18,22,27] ' dir.
18 sayısı dizinin ortasında bulunduğu için Avarage case kapsamına girer.

## SORU 4:
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## CEVAP 4:
1. Adım = dizinin en küçük elemanı 2 olduğundan ve 2'nin başa gelmesi gerektiğinden dolayı 2 ile 7 yer değiştirir. [2,3,5,8,7,9,4,15,6]
2. Adım = dizinin en küçük elemanları 2 ve 3 olmaları gereken yerlerde. Sırada 3'ten büyük en küçük eleman 4 olduğundan dolayı 4 ile 5 yer değiştirir. [2,3,4,8,7,9,5,15,6] 
3. Adım = Şimdi sırada 4'ten büyük en küçük eleman olan 5 var. 5 ile 8'in yeri değişmeli. [2,3,4,5,7,9,8,15,6]
4. Adım = 5'ten büyük en küçük eleman 6 olduğundan dolayı 6 ile 7'nin yeri değişmeli. [2,3,4,5,6,9,8,15,7] olur.


