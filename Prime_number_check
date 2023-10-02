#include<iostream>
#include<cmath>

using namespace std;

bool p_num(int a){

	bool c;

	for(int i=1;i<=a;i++){

		if(a==1){
		
			c = true;
			break;
		}

	
		else if(a%i==0 and i==a){
		
			c = true;
		}
		else if(a%i==0 and (i!=a and i!=1)){
		
			c = false;
			break;
		}
	}

	return c;

}

int main(){

	int a;

	cout << "Enter the number you want to check for prime "<< endl;
	cin >> a ;

	if(p_num(a)){
	
		cout << a << " is a prime number"<< endl;
	}
	else{
	
		cout << a << " is not a prime number "<< endl;
	}
     	
	return 0;


}
