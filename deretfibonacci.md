## Deret Fibonacci
```c
int main ()
{
int a,b,c,n;
	a=1;
	b=1;
	cout <<"Baris Bilangan Fibonacci \n";
	cout <<"\n Masukkan Banyak Bilangan :";cin>>n;
	cout <<" "<<a<<" "<<b<<" ";
	n=(n-2);
	for (c=1;c<=n;c++){
	if (c%2==1)
	{
	a=a+b;
	cout<<a<<" ";
}else{
	b=a+b;
	cout<<b<<" ";
	}}
	
}	
```
