# sistema-bancário

Este é um projeto de sitema bancário  desenvolvido em python. Ele exibe a operações de sacar, deposito, extrato e sair.
#Estrutura do Projeto


## Funcionalidades

Esse programa é um simulador de operações bancárias básicas, como depósito, saque e visualização de extrato.

-Depósito (d): Quando o usuário seleciona 'd', ele é solicitado a inserir o valor do depósito. Se o valor for positivo, ele é adicionado ao saldo e uma linha é adicionada ao extrato indicando o depósito. Se o valor for negativo ou zero, uma mensagem de falha é exibida.

-Saque (s): Ao selecionar 's', o usuário insere o valor que deseja sacar. O programa verifica várias condições antes de permitir o saque: se há saldo suficiente, se o valor excede o limite de saque e se o número máximo de saques já foi atingido. Se todas as condições forem atendidas, o valor é deduzido do saldo, uma linha é adicionada ao extrato indicando o saque, e o número de saques é incrementado.

-Extrato (e): A opção 'e' permite ao usuário visualizar seu extrato, que inclui todas as transações feitas até o momento, bem como o saldo atual.

-Sair (q): Essa opção termina o programa, encerrando o loop while.

## Tecnologias Utilizadas

- Python

## Autor

Este projeto foi desenvolvido por Yara Mendes(https://github.com/yamendes05).


