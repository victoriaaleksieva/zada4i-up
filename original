// ConsoleApplication30.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
int main()
{
	int arr[100] = { 0 };
	int n;
	std::cin >> n;
	int temp = 0;
	int counter = 0;

	for (int i = 0; i < n; i++)
	{
		std::cin >> arr[i];
	}
	for (int i = 0; i < n; i++)
	{
		for (int j = i + 1; j < n; j++)
		{
			if (arr[j]==arr[i])
			{
				arr[i] = 0;
				counter++;
			}
		}
	}
	for (int i = 0; i < n; i++)
	{
		for (int j = i + 1; j < n ; j++)
		{
			if (arr[j] < arr[i])
			{
				temp = arr[i];
				arr[i] = arr[j];
				arr[j] = temp;
			}
		}
	}
	std::cout << "the second min is " << arr[counter + 1] << '\n' <<"the second max is "<< arr[n - 2];
   

	
}
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file
