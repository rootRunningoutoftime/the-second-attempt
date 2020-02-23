# the-second-attempt
the hypothesis phase


    #include <iostream>
    #include <string.h>    
    #include<assert.h>
    using namespace std;
    int main()
    {
	int TheInput = 0;
    cout << "This program will calculate how many squares are required to give the inventor at least 1000 grains of rice, at least 1,000,000 grains, and at least 1,000,000,000 grains.You'll be able to keep track of which square you are at, an int to keep the number of grains on the current square and an int to keep track of the grains on all previous squares. As soon as you put in an input " <<endl;
	cin >> TheInput;
	switch (TheInput) {
	case'':
		while (TheInput <= 1000) {
			cout << I << ’\t’ << 1000 / square(theinput) << ’\n’;
			cout << ” the remainder is : ” 1000 % square(theinput) << endl;
			++I;
		}
		break;
	case'':
		while (TheInput <= 1000000) {
			cout << I << ’\t’ << 1000000 / square(Theinput) << endl;
			cout << "the remainder is” << 1000000 % square(I) << endl;
			++I;
		}
		break;
	case'-':
		while (TheInput <= 1000000000) {
			cout << I << ’\t’ << 1000000000 / square(Theinput) << ’\n’;
			cout << "the remainder is :” 1000000000 % square(Theinput) << endl;
			++I;
		}
    cout << "Sorry that number is invalid please type in another one \n";
}
