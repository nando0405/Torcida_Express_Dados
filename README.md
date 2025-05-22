# Torcida_Express_Dados
## 👥 Integrantes do Grupo

- Nome: FELIPE DA ROCHA PINHEIRO  
  Matrícula: 22.222.059-2 
- Nome: FERNANDO DOMINGUES   
  Matrícula: 22.122.034-6   
- Nome: GUILHERME MATIAS R DE SOUZA 
  Matrícula: 

---

## 📄 Descrição

Este projeto consiste em um banco de dados relacional para gerenciamento de **torcedores**, **times de futebol**, **companhias aéreas**, **voos**, **estádios** e **pacotes de viagem** que incluem ingressos e deslocamento para jogos.

---

## 🗃️ Estrutura do Projeto

- `ddl.sql`: script de criação das tabelas e relacionamentos do banco de dados.
- `insert.sql`: script de inserção de dados nas tabelas.
- `questoes.sql`: consultas SQL com base nos dados do projeto.

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

- PostgreSQL instalado (ou outro SGBD compatível)
- Uma ferramenta cliente como pgAdmin, DBeaver ou o terminal do próprio PostgreSQL

### Passo a passo

1. **Criar um banco de dados:**

   No PostgreSQL:
   ```sql
   CREATE DATABASE futebol_viagens;

2. **Executar o script de criação das tabelas (ddl.sql):**
  No terminal ou pgAdmin:

       \c futebol_viagens
        \i caminho/para/ddl.sql
   
3.**Executar o script de inserção dos dados (insert.sql):**

    \i caminho/para/insert.sql
  
4.**Executar as consultas (questoes.sql)**:

    \i caminho/para/questoes.sql

  
**As consultas vão exibir resultados como:**

- Torcedores e os times que torcem

- Voos e companhias aéreas

- Pacotes comprados e formas de pagamento

- Estádios com maior capacidade

- E outras informações úteis

Obs úteis 💡:

- Os scripts foram projetados para funcionar com PostgreSQL.

- O ddl.sql possui comandos DROP TABLE IF EXISTS para garantir recriação limpa.

- Há integridade referencial entre todas as tabelas via FOREIGN KEY.

**Diagrama relacional**

![image](https://github.com/user-attachments/assets/e89cc701-8b38-4944-a865-92585d9c14f8)
