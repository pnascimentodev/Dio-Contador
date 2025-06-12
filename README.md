# Projeto Contador

Este projeto é um exercício prático de controle de fluxo em Java, onde implementamos um sistema que realiza a contagem entre dois números inteiros.

## Funcionalidades

- Recebe dois números inteiros como parâmetros via terminal
- Valida se o segundo número é maior que o primeiro
- Realiza a contagem do número de iterações entre os dois parâmetros
- Imprime cada número da sequência no console

## Estrutura do Projeto

O projeto contém as seguintes classes principais:

- `Contador.java`: Classe principal que contém a lógica do programa
- `ParametrosInvalidosException.java`: Classe de exceção personalizada para tratamento de erros

## Como Executar

1. Certifique-se de ter o Java e o Maven instalados em sua máquina
2. Clone o repositório
3. Navegue até o diretório do projeto
4. Execute o comando:
   ```bash
   mvn clean install
   ```
5. Execute a classe Contador:
   ```bash
   java -cp target/classes com.seuprojeto.contador.Contador
   ```

## Como Usar

1. Ao executar o programa, você será solicitado a digitar dois números:
   - Primeiro parâmetro: número inicial
   - Segundo parâmetro: número final
2. O programa irá:
   - Validar se o segundo número é maior que o primeiro
   - Calcular o número de iterações
   - Imprimir a sequência de números

## Exemplo de Uso

```
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```

## Tratamento de Erros

O programa inclui tratamento de exceções para casos onde:
- O primeiro parâmetro é maior que o segundo
- Neste caso, uma mensagem de erro será exibida: "O segundo parâmetro deve ser maior que o primeiro"

## Tecnologias Utilizadas

- Java
- Maven
- JUnit (para testes)
