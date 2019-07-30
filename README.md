# greatest-no.-using-constructor
among 3 integer



#include<iostream>
using namespace std;
class text{
	int a,b,c;
	public:
		text()
		{ a=10;
		b=20;
		c=30;
		}
		void greatest()
		{ int x;
	x=(a>c&&a>b)?a:((b>a&&b>c)?b:c);
		cout<<"greatest no. is"<<x;
		}
};
int main()
{ text t;
t.greatest() ;
}
