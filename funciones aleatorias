#include <iostream>
#include <cstdlib>
#include <ctime>
#include <vector>

using namespace std; 

int aleatorio()//funcion aleatorio para la generarcion de los numeros
{
    return rand() % 100;
}

bool esImpar(int numero)//funcion para que losnumeros leatorios sean impares
{
    return numero % 2 != 0;
}

int main(int argc, char *argv[])
{
    int n, c = 0, num;
    cout << "Generar N numeros impares, ingrese N: "; // Solicitar al usuario la cantidad de números para generar
    cin >> n;


    while (c < n)// se ejecuta mientras la condición sea verdadera
    {
        num = aleatorio();
        if (esImpar(num))
        {
            c++;
            cout << "impar[" << c << "]: " << num << endl; // Imprimir los numeros impar generado
        }
    }

    return 0; 
}

