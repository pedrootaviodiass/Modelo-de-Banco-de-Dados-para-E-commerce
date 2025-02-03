# 📦 Modelo de Banco de Dados para E-commerce

## 📌 Descrição do Projeto
Este projeto apresenta um modelo conceitual refinado para um sistema de e-commerce, contemplando clientes (PF e PJ), formas de pagamento, status de entrega e rastreamento de pedidos. O esquema foi desenvolvido para atender aos requisitos do desafio proposto.

## 📊 Estrutura do Banco de Dados
O modelo de banco de dados foi atualizado para incluir os seguintes elementos:

### 1️⃣ **Cliente (Pessoa Física e Pessoa Jurídica)**
- A entidade **Cliente** agora está separada em:
  - **Pessoa Física (PF)**: Nome, CPF, Data de Nascimento.
  - **Pessoa Jurídica (PJ)**: Razão Social, CNPJ, Nome do Representante.

### 2️⃣ **Pagamento**
- Os clientes podem ter múltiplas formas de pagamento cadastradas.
- Campos principais: ID do Pagamento, Tipo (Crédito, Débito, Boleto, etc.), Dados do Cartão (se aplicável).

### 3️⃣ **Entrega**
- A entidade **Entrega** foi criada para armazenar informações sobre o status e rastreamento dos pedidos.
- Campos principais: ID da Entrega, Status da Entrega (Aguardando, Enviado, Entregue, etc.), Código de Rastreio, Data Prevista.

## 📌 Tecnologias Utilizadas
- **Banco de Dados Relacional** (MySQL, PostgreSQL, ou outro SQL)
- **Ferramentas de Modelagem**: MySQL Workbench, DBDesigner, ou similar

## 📝 Como Utilizar
1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
