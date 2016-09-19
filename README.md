# Cplusplus_lessons
# learning to code C++

#include <iostream>


int main() {

	int x;
	int y;

	int z;

	x = 2;
	y = 3;

	z = x + y;

	std::cout << z;


	z = z * 2;

	std::cout << "\n\n" << z;

	int i = 0;
		for (i; i < 10; i = i + 1) {

			z = z * 2;
			std::cout << "\n\n" << z;
		}

		i = 0;
		z = 5;
		while (i < 10) {
			z = z * 2;
			std::cout << "\n\n" << z;
			i = i + 1;
		}

		i = 0;
		z = 0;
		while (i < 10) {

			if (z % 2 == 0)
			{
				std::cout << "\n\n" << z;
		}
			else 
			{
				std::cout << "\n\n" << 0;
			}
			i = i + 1;
			z = z + 1;
		}



	int a;
	std::cin >> a;
	return 0;
}
