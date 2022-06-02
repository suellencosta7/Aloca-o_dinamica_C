// ALOCAÇÃO DINÂMICA


#include <iostream>
#include <stdlib.h> //Para ocorrer a alocação, é necessário inserir a biblioteca stdlib.
using namespace std;


int main(){ 

 int *ponteiro;
 ponteiro = (int*) malloc(sizeof(int)); // Função malloc(), aloca um bloco de bytes em memória, usamos o sizeof para definir o tamano em bytes quando não se sabe.
	
	if(ponteiro == NULL){
			printf("Erro!\n"); // Se não encontrar valor na memória, retorna nulo e printa a mensagem ERRO!
		
	} else {
	
	       *ponteiro=10;	// Caso encontre,recerá 10.
	    	printf("Valor recebido %d",*ponteiro);
	    	free(ponteiro); //Desalocamento,libera o espaço de memória alocado a um ponteiro
		
		/*	Todas as vezes que ocorrer a alocação de memória, faça a liberação de espaço ao terminar */
		
		
	}
	 
  }
