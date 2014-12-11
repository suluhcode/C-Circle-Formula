C-Circle-Formula
================
C++ with simple algorithm
#include <stdio.h> // Memasukan semua fungsi yang ada di studio.h
#define phi 3.14 //deklarasi phi=3.14
int main() //pprogram berjalan dalam fungsi main
{
int a; float luas; //deklarasi variabel dengan integer dan float
printf("masukkan jari-jari lingkaran:"); //Memasukan jari jari
scanf("%d",&a); //fungsi scan untuk menyimpan input
luas=phi*a*a; //proses rumus dengan menngunakan variabel baru luas
printf("luas lingkaran adalah:%.2f",luas); //print out hasil dengan mamnggil variabel luas
printf("\n\n            Program by: Ade Suluh");
}
