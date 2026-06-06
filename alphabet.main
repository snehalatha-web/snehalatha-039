#include <iostream>
#include <string>
using namespace std;

int main() {
    string s;
    cin >> s;
    int flag = 0;

    for (int i = 0; i < s.size(); i++) {
        flag = flag | (1 << (s[i] - 'a'));
    }

    cout << ((flag == (1 << 26) - 1) ? "yes" : "no");
    return 0;
}
