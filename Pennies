#include <stdio.h>
#include <cs50.h>
#include <math.h>

int main(void)
{
    double total;
    int days, start;
    do
    {
        days = get_int("Enter number of days: ");
    }
    while (days < 28 || days > 31);

    do
    {
        start = get_int("Amount of pennies: ");
    }
    while (start < 1);

    for (int i = 0; i < days; i++)
    {
        total = total + start * pow(2, i);
    }
    printf("$%.2f\n", total / 100);

}
