Write a program that calculates the area of a rectangle (width*length).  The program should be based on the following functions:
•	int getLength( )
•	int getWidth( )
•	int CalculateArea( )
•	void DisplayArea( )

#include <iostream>

using namespace std;

int getLength();
int getWidth();
int calArea();
void disArea();

int main()
{
	disArea();

}
int getLength() {
	int len;
	cout << "\n Enter The Length:\t";
	cin >> len;
	cout << endl;
	return len;
}
int getWidth() {
	int wid;
	cout << "\n Enter The Width:\t";
	cin >> wid;
	cout << endl;
	return wid;
}
int calArea() {
	int getL, getW;
	int cal;
	getL = getLength();
	getW = getWidth();
	cal = getL * getW;
	return cal;
}
void disArea() {
	int area = calArea();
	cout << "\n The Area of the Rectangle is: \t" << area;
}

