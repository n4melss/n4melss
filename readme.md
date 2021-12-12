```cpp
#include <iostream>
#include <string>
#include <vector>

struct strings {
	std::string name;
	std::string country;
	std::string mainProgrammingLanguages;
};

int main(void) {
	std::vector<strings> profile(10);
	profile[0].name = "Leon";
	profile[0].country = "Germany";
	profile[0].mainProgrammingLanguages = "JavaScript";

	std::cout << "My name is " + profile[0].name + ", I  come from " + profile[0].country + " and my main programming language is " + profile[0].mainProgrammingLanguages + ". I also work with TypeScript, Python, C ++, C and C#.";
	return 0;
}
```
