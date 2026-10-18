#include <iostream>
using namespace std;

// Function to calculate the Binomial Coefficient
int BinoCoef(int n, int k)
{
    int res = 1;  // Stores the result

    // Calculate the Binomial Coefficient
    for(int i = 0; i < k; i++)
    {
        res *= (n - i);
        res /= (i + 1);
    }

    return res;
}

// Function to print Pascal's Triangle
void printPascal(int n)
{
    // Loop for each row
    for(int l = 0; l < n; l++)
    {
        // Print elements in each row
        for(int m = 0; m <= l; m++)
        {
            cout << BinoCoef(l, m) << "\t";
        }
        cout << endl;  // Move to next row
    }
}

int main()
{
    int rows;

    // Take number of rows from the user
    cout << "Enter number of rows: ";
    cin >> rows;

    // Print Pascal Triangle
    printPascal(rows);

    return 0; 
}
