# 💼 Java Employee Salary Manager

Este é um projeto simples em Java que simula o gerenciamento de salário de um funcionário. O programa realiza:

- Entrada dos dados do funcionário
- Cálculo do salário líquido (salário bruto - imposto)
- Aumento percentual do salário
- Exibição de dados atualizados

## 🧠 Conceitos Utilizados

- Programação orientada a objetos (POO)
- Encapsulamento de lógica em classes
- Entrada de dados via terminal
- Cálculos com ponto flutuante
- Uso de pacotes (`application`, `entities`)

## 📂 Estrutura do Projeto
src/
├── application/
│ └── Program.java
└── entities/
└── Employee.java
## ✅ Como Usar

1. Compile os arquivos:
   ```bash
   javac application/Program.java entities/Employee.java
2.Execute o programa:
    java application.Program
3. Forneça os dados solicitados no terminal.

📌 Exemplo de Entrada/Saída
  Name: João Silva  
  Gross salary: 5000.00  
  Tax: 1000.00  

  Employee: João Silva, $4000.00  

  Which percentage to increase salary? 10  

  Updated data: João Silva, $4500.00

🛠️ Classe Employee
A classe Employee deve conter:

Atributos:

name: nome do funcionário

grossSalary: salário bruto

tax: valor do imposto

Métodos:

netSalary(): retorna o salário líquido

increaseSalary(double percentage): aumenta o salário bruto em determinada porcentagem

toString(): formata os dados do funcionário para exibição

📄 Licença
Este projeto é voltado para fins educacionais e estudos de programação orientada a objetos em Java.
