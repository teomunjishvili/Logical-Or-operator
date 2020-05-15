#include<iostream>
using namespace std;
main()
{
    int number;
    cout<<"Please enter a number: ";
    cin>>number;
    if((number%2 == 0) || (number>4))
        cout<<"True";
    else
        cout<<"False";

/*if the entered number is even and greater than 4, the output will be "True", since True || True =True;
 *if the entered number is even and less than 4, the output will be "True", since True || False =True;
 *if the entered number is odd and greater than 4, the output will be "True", since False || True = True;
 *if the entered number is odd and less than 4, the output will be "False", since False || False = False;
 */

 return 0;
}
