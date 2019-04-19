#include "pch.h"
#include <iostream>

using namspace std;
 int main() {
 int a,b ;
 float KetQua = 0;
 cout<< "nhap gia tri he so a,b:"
 cin>> a >> b;
 if(a == 0&& b == 0) {
 cout << "phuong trinh co vo so nghiem" << endl;
 }
 else if(a == 0 && b !=0) {
 cout <<"phuong trinh vo nghiem"<< endl;
 }
 else{
 KetQua=-b*1.0/a;
 cout<<"nghiem phuong trinh"<<a<< "x"<<"+"<<b<<"=0"<<KetQua<<endl;
 
 }
 return 0;
