# Praktikum9 soal 6.3 a
Penjelasan :
 mendeklarasikan sebuah variable ARRAY dengan tipe data integer dengan nilai yang telah diisi secara acak.
kemudian definisikan dua buah variable dengan tipe data integer yaitu variable MAX dan MIN.
lakukan perulangan yang dimulai dari (0) sampai dengan banyaknya index pada Array dikurangi 1…kenapa harus dimulai dari 0?karena index pada suatu array dimulai dengan index (0)  ..dan kenapa harus dikurangi 1? karna jika tidak, maka  jumlah perulangan akan melebihi jumlah index pada ARRAY.. 
lalu buat dua buah kondisi dalam perulangan: kondisi pertama – untuk membandingkan nilai yang terdapat pada ARRAY (mis: nilai[a]) dengan nilai MAX. jika nilai pada ARRAY lebih besar (>) dari nilai MAX, maka nilai MAX digantikan dengan nilai pada ARRAY tersebut (MAX=nilai[a]). kondisi ini nantinya akan mendapatkan nilai terbesar dari deretan bilangan pada ARRAY.  kondisi kedua : untuk membandingkan nilai yang terdapat pada ARRAY (mis:nilai[a]) dengan nilai MIN. jika nilai pada ARRAY lebih kecil (<) dari nilai MIN, maka nilai MIN digantikan dengan nilai pada ARRAY tersebut (MIN=nilai[a]). kondisi ini nantinya akan mendapatkan nilai terkecil dari suatu deretan bilangan pada ARRAY.

soal 6.3 b
Menentukan modus dari n buah data berupa bilangan bulat, di mana besar datanya antara 1
sampai dengan 10.
procedure maksimum(data : larik; n : integer;output maks, item : integer)
{ procedure ini hasil modifikasi dari algoritma (…) karena selain nilai maks dari larik data, juga
perlu diketahui besar datanya item }
Deklarasi
i : integer
Deskripsi
maks <= data[1]
item <= 1
for i <= 2 to n do
if (data[i] > maks) then
maks <= data[i];
item <= i;
endif
endfor
