# Modelo-Entidade-Relacionamento---E-Commerce
Este repositório contém a modelagem completa de um banco de dados relacional para um sistema de e-commerce, desenvolvido com foco em normalização, flexibilidade e boas práticas de modelagem conceitual. O projeto foi criado com fins acadêmicos e de estudo, sendo uma base sólida para sistemas comerciais reais.

Principais características
- Clientes Pessoa Física e Jurídica separados com herança simulada via chave primária estrangeira.
- Pedidos com rastreio de entrega e status, permitindo o acompanhamento do ciclo do pedido.
- Múltiplas formas de pagamento por cliente.
- Gestão de produtos com estoques, fornecedores e múltiplos vendedores.
- Relacionamento N:N entre pedidos e produtos, com quantidade associada.
- Estrutura modular e expansível, ideal para sistemas escaláveis.

Entidades modeladas
- ClienteBase, ClientePF, ClientePJ
- Pedido, Entrega, Pagamento
- Produto, Estoque, Fornecedor, Terceiro-Vendedor

Tabelas de relacionamento: Produto por Vendedor, Produto_has_Estoque, Relação_Produto_Pedido, Disponibilizando

Ferramentas utilizadas
- MySQL Workbench para modelagem EER

![Bd](https://github.com/user-attachments/assets/acafe87f-f6f8-4b33-9fd6-e9ff0a3ad146)
