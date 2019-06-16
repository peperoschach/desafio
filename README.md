# Desafio
> Lavação de Veículos

[![Downloads Stats][npm]][npm-url]
[![Downloads Stats][angular]][angular-url]
[![Downloads Stats][typescript]][typescript-url]


## Instruções

1. Crie 4 classes em TypeScript, sendo elas 'Veículo', 'Carro', 'Esportivo' e 'Caminhão'. 
2. As classes 'Carro' e 'Caminhão' devem extender a classe 'Veculo'. E a classe 'Esportivo' deve extender a classe 'Carro', pois será um 'Carro Esportivo'.

3. A classe 'Veiculo' deve conter os seguintes campos: nome(string), rodas(number) e ligado(boolean).
4. E os seguintes métodos: buzinar(retornar uma string) e ligarDesligar(retornar void e alterar o valor da variavel 'ligado')

```sh 
Atenção: A buzina do caminhão deve ser mais potente do que a de um carro!
```
5. Escreva uma função que lave o veículo, indicando quantas portas foram lavadas e que ao término faça com que o veículo buzine e desligue o motor.
6. Após terminar a implementação, refatore a aplicação usando módulos 

A saída deverá ser assim:

```sh
O veículo está: desligado
Agora o veículo está: ligado
Agora o Ford Ka está entrando na lavação
Lavando o exterior... Lavando as 4 rodas
O veículo buzina: Beep Beep!
Agora o veículo está: desligado


O veículo está: desligado
Agora o veículo está: ligado
Agora o Ferrari está entrando na lavação
Lavando o exterior... Lavando as 4 rodas
O veículo buzina: Beep Beep!
Agora o veículo está: desligado


O veículo está: desligado
Agora o veículo está: ligado
Agora o Mercedez está entrando na lavação
Lavando o exterior... Lavando as 18 rodas
O veículo buzina: Beeeeeeeeeeeep Beeeeeeeeeeeep!!!
Agora o veículo está: desligado

```
 



 [angular]:https://img.shields.io/badge/angular-6.0.8-red.svg
[angular-url]:https://angular.io/
[typescript]:https://img.shields.io/badge/typescript-3.5.1-blue.svg
[typescript-url]:https://www.typescriptlang.org/ 
[npm]:https://img.shields.io/badge/npm-6.4.1-green.svg
[npm-url]:https://www.npmjs.com/