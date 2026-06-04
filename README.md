# coding.practice1
 //find the chosen number 's frequency 
#include <iostream>
using namespace std;
#include <vector>
int main()
{
    int m;
    int n;
    vector<int> s;
    int count = 0;
    int num;
    // cout << "输入整数序列长度n(n<=100)" << endl;
    cin >> n;
    // cout << "请输入数据" << endl;
    for (int i = 0; i < n; i++)
    {
        cin >> num;
        s.push_back(num);
        // cout << "下一个" << endl;
    }
    // cout << "请输入一个特定数据m" << endl;
    cin >> m;
    for (int i = 0; i < n; i++)
    {
        if (s[i] == m)
        {
            count++;
        }
    }
    cout << count;
    // cout << "在输入的数据中有" << count << "个与你刚才指定的数据相等的";
}
