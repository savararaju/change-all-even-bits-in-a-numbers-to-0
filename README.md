# change-all-even-bits-in-a-numbers-to-0




#include<bits/stdc++.h>
using namespace std;

class Aditya
{
    public:
  long long int convertEvenBitToZero(long long int n) {
        return (n & 0xAAAAAAAA);
    }
};

int main()
{
int t;
cin >> t;
while(t--)
{
int K.N;
cin >> K >> N;
Aditya ob;
int ans = ob.setKthBit(int N, int K);
cout << ans << end;
}
return 0;
