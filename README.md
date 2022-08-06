# InsertionSortProject
[22,27,16,2,18,6] dizisini Insertion Sort algoritması yardımıyla sıralamak için;

Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.  [22,27,16,2,18,6]
Daha sonra 27 ile 22 kıyas edilir. 20 < 27 olduğu için 22 başta kalır.
Şimdi de üçüncü eleman olan 16 ile 27 kontrol edilir. 16 < 27 ancak aynı zamanda 16 < 22 olduğundan 16 sayısı en başa alınır ve sayılar sırasına göre kaydırılır. Dizinin yeni hali: [16,22,27,2,18,6] olur.
Bu adımda da sıra dördüncü eleman yani 2 sayısına bakmaya gelmiştir. 1 hepsinden küçük olduğu için direk sola kaya kaya en başa yerleşir ve diğer sayılarda birer sağa kayarak kendi sırasını alırlar. Dizinin son hali: [2,16,22,27,18,6] olacaktır.
Dizinin son hali ise : [2,6,16,18,22,27] olarak sıralanmış olur.
Big-O gösterimi: 
n(n+1)/2 O(n^2) 18 sayisi Average Case
