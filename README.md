# 16.-odev

//karenin alan�n� hesaplayan fonksiyon

#include<stdio.h>

int karealan(int);

int main(void)
{
	int x,sonuc;
	
	printf("karenin bir kenarini giriniz:");
	scanf("%d" , &x);
	
	sonuc=karealan(x);
	
	printf("alan: %d" , sonuc);
	
	return 0;
}

int karealan(int x)
{
	int alan;
	
	alan=x*x;
	
	return alan;
}
