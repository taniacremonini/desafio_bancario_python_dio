
 # Python- sistema_bancario.py
## 🧪 Exemplo de Uso
Após iniciar o programa, você verá o menu abaixo:

================ MENU ================

[d] Depositar

[s] Sacar

[e] Extrato

[nc] Nova conta

[lc] Listar contas

[nu] Novo usuário

[q] Sair

=>


### 1. Criando um novo usuário

Você deve informar:

- CPF (somente números)
- Nome completo
- Data de nascimento (dd-mm-aaaa)
- Endereço (formato: rua, número - bairro - cidade/UF)

### 2. Criando uma nova conta

Informe o CPF do usuário já cadastrado para vincular a conta.

### 3. Realizando um depósito

Informe o CPF do cliente e o valor a ser depositado.

### 4. Realizando um saque

Informe o CPF e o valor. Lembre-se das **regras de saque**:

- Máximo de R$500 por saque
- Limite de 3 saques por dia

### 5. Visualizando o extrato

O sistema exibirá todas as transações realizadas (saques e depósitos) com os respectivos valores e datas.

---

## 🛠 Organização do Código

O projeto é dividido em:

| Arquivo/Função         | Responsabilidade                                 |
|------------------------|--------------------------------------------------|
| `Cliente`, `PessoaFisica` | Representação de usuários                      |
| `Conta`, `ContaCorrente` | Lógica das contas e validações de operações     |
| `Historico`             | Armazena transações da conta                     |
| `Transacao`, `Saque`, `Deposito` | Executa e registra operações financeiras |
| Funções como `depositar`, `sacar`, `criar_cliente` | Interação com usuário |

---

## 💡 Dicas para Estudo

- Explore os conceitos de **classe abstrata**, **encapsulamento**, **herança** e **polimorfismo** usados no projeto.
- Tente implementar **testes automatizados** com `unittest` para as classes.
- Modifique a lógica para permitir que o usuário escolha entre múltiplas contas associadas ao mesmo CPF (implementação pendente marcada como `FIXME`).

---

## Requisitos
Python 3.x

Bibliotecas utilizadas: datetime, textwrap, abc

## 📌 Regras de Negócio
Saques limitados a R$500 por operação.

Máximo de 3 saques por conta ao dia.

CPF não pode ser duplicado entre usuários.

Cada cliente pode ter múltiplas contas.



## 👩‍🎓 Projeto Acadêmico
Projeto desenvolvido no contexto desafio Python Dio, com foco em:

Programação Orientada a Objetos (POO)

Encapsulamento, herança e abstração

Modelagem de dados e operações bancárias básicaslo do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é

