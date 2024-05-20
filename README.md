


#Proje Insertion Sort#

a)Verilen dizinin sort türüne göre aşamalarını yazınız. [22,27,16,2,18,6]
b)Big-O gösterimini yapınız.
c)Time Complexity.
d)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
e)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


a) [22,27,16,2,18,6] Başlangıç
- [2,27,16,22,18,6] 2-22 yer değiştirdi.
- [2,6,16,22,18,27] 6-27 yer değiştirdi.
- [2,6,16,18,22,27] 18-22 yer değiştirdi.


b) n+(n-1)+(n-2)+(n-3)+(n-4)+1 = n*(n-1)/2
= n^2*(-n)/2
= O(n^2)


c) Time Complexity
  -Avarage Case = Aranılan değerin ortada olması [22,27,16,2,18,6] "Örnek a da aranılan değer ortadadır örnek olarak gösterilebilir"
  -Worst Case = Aranılan değerin en sonda olması
  -Best Case= Aranılan değerin en başta olması 
  
 d) Sıralama yapıldıktan sonra 18 sayısı dizinin başında ya da sonunda bulunmaz. Bu yüzden Avarage Case kapsamına girer.
 
 
 e)[7,3,5,8,2,9,4,15,6] Başlangıç
 -[2,3,5,8,7,9,4,15,6] 2-7 yer değiştirir.
 -[2,3,4,8,7,9,5,15,6] 4-5 yer değiştirir.
 -[2,3,4,5,7,9,8,15,6] 5-8 yer değiştirir.
 -[2,3,4,5,6,9,8,15,7] 6-7 yer değiştirir.
 
   
