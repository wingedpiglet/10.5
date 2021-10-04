#include<iostream>
using namespace std;

int  main() {
	char input = 'o';
	

	while (input != 'q') {
		cout << "choose your items" << endl;
		cin >> input;
		switch (input) {
		case 'a':
			cout << "recieved 1 arrow" << endl;
			break;
		case's':
			cout << "Recieved 5 arrows" << endl;
			break;
		case'r':
			cout << "recieved restless cricket!" << endl;
			break;
		case  'h':
			cout << "recieved Hot-footed frog" << endl;
		case 'o':
			cout << "octo balloon" << endl;
			break;
		default:
			cout << "not an option, dummy." << endl;
		}
	}
}
