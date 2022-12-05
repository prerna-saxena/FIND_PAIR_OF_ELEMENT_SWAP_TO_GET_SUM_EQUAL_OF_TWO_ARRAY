# FIND_PAIR_OF_ELEMENT_SWAP_TO_GET_SUM_EQUAL_OF_TWO_ARRAY



#include <iostream>
using namespace std;

int getSum(int x[], int n)
{
    for(int i=0; i<n; i++){
        sum=sum+x[i];
        return sum;
    }
void findswapvalues(int a[], int n, int b[], int m)
int sum1=getSum(a, n);
int sum2=getSum(b, m);

int newsum1, newsum2, val1, val2;
for(int i=0; i<n; i++){
    for(int j=0; j<m; j++){
        newsum1= sum1- a[i]+b[j];
        newsum2= sum2- b[j]+a[i];
        if(newsum1==newsum2)
        {
            val1=a[i];
            val2=b[j];
        }
    }
}
cout<<val1<<" "<<val2;
}
