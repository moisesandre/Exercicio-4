# Exercicio4

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i;

    for (i=1; i<=500; i++)
    {
        if (i % 5 == 0)
        {
            printf("Numeros multiplos de 5 sao: %d\n",i);
        }
    }

    return 0;
}
