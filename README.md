1.) Resposta: 
#include <stdio.h>

int main(){

    int indice=13, soma=0;

    for(int k=1; k<=indice; k++){
        soma +=k;
    }

    printf("%i", soma);
    return 0;
}

2.) Resposta:
#include <stdio.h>

int fibo(int num) {
    int f1 = 0, f2 = 1, f;
    
    if (num == 0 || num == 1){
        return 1;

    }
        
    for (f = 1; f < num; f = f1 + f2) {
        f1 = f2;
        f2 = f;

    }
    
    if (f == num){
        return 1;

    }
    
    else{
        return 0;

    }
}

int main() {
    int num;
    
    printf("Digite um numero: ");
    scanf("%i", &num);
    
    if (fibo(num)){
        printf("%i Pertence a sequencia.", num);

    }

    else{
        printf("%i Nao pertence a sequencia", num);

    }
        
    return 0;
}

3.)Resposta: 
a) 1,3,5,7,9
b) 2,4,8,16,32,64,128
c) 0,1,4,9,16,25,36,49
d) 4,16,36,64,100
e) 1,1,2,3,5,8,13
f) 2,10,12,16,17,18,19,21

4.)Resposta: 
Não Entendi o Enunciado.

5.)Resposta: 
#include <stdio.h>
#include <string.h>

int main(void){

    char texto[100];

    printf("Escreva algo: ");
    scanf(" %s",&texto);

    for (int i=9;i>=0;i--){
        printf("%c",texto[i]);

    }

    return 0;
}
