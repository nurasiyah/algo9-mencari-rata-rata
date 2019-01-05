# algo9-mencari-rata-rata

## coding program

#include<iostream.h>
#include<conio.h>
main(){
float input,max,min,total,rata,t,batas;
cout<<“PROGRAM MENGHITUNG NILAI RATA-RATA, MAXIMUM DAN MINIMUM\n”;
cout<<“*******************************************************\n\n”;
cout<<“Masukkan Jumlah Siswa : “;   cin>>batas;
for(t=1;t<=batas;t++){
cout<<“Masukan Nilai Siswa “<<t<<” : “;cin>>input;
total=total+input;
if(input>max){
max=input;
}
if(input<min||t==1){
min=input;
}
}
rata=total/batas;
cout<<“\n________________________”;
cout<<“\nNilai Rata – Rata : “<<rata;
cout<<“\nNilai Maximum\t  : “<<max;
cout<<“\nNilai Minimum\t  : “<<min;
getch();
}
