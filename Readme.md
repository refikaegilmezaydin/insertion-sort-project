# Soru 1: [22,27,16,2,18,6] -> Insertion Sort

## 1.1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
### Cevap 1.1: Insertion Sort türünde soldan sağa doğru dizi elemanları küçükten büyüğe sıralanırken yer değiştirilerek sıralama sağlanır. Bu işlemin tekrarı da dizinin eleman sayısına göre değişeceğinden örneğin sıralama aşamaları şu şekilde yürüyecektir:
		1.işlem: [2,27,16,22,18,6]
		2.işlem: [2,6,16,22,18,27]
		3.işlem: [2,6,16,18,22,27]

## 1.2.	 Big-O gösterimini yazınız.
### Cevap 1.2: Insertion Sort türü sıralamalarda O (n^2) şeklindedir.

## 1.3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

### Cevap 1.3: Bu dizinin sıralanmasının ardından elemanları arasında;
1.3.1.1.	Best Case:2
1.3.1.2.	Worst Case:27
1.3.1.3.	Average Case: 16,18 şeklinde olur.

## 1.4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
### Cevap 1.4: Sıralanan dizinin son hali  [2,6,16,18,22,27] şeklinde olduğundan 18 sayısı Average Case kapsamında olur.
--------------------------------------------------------------------------------------------------------------------------


# Soru 2:  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
	### Cevap 2: [7,3,5,8,2,9,4,15,6] ana dizi
	1.İşlem: [2,3,5,8,7,9,4,15,6]
	2.İşlem: [2,3,4,8,7,9,5,15,6]
	3.İşlem: [2,3,4,5,7,9,8,15,6]
	4.İşlem: [2,3,4,5,6,9,8,15,7] şeklinde olacaktır. 

[Kodluyoruz Sayfamız](https://www.patika.dev/)