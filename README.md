
# Instruções

- Deve ser feito em NodeJS, pode ser TypeScript.
- Evite usar pacotes extras para funcionalidades simples.
- Deve persistir os dados em um banco de dados (voce escolhe qual banco usar).
- Apenas o nivel especificado pelo email é requerido, os outros não serão avaliados.
- Seguir padroes REST.
- Cada nivel é uma expansão do anterior, portanto caso queira incorporar seu teste com outras funcionalidades dos outros niveis sinta-se avontade.
- Usar git para controle de versionamento

## Nivel 1:

Construa um CRUD que permita controlar os clientes de um sistema.

**Requisitos**
- Cada usuario deve ter no minimo email, nome e cpf
- Campos obrigatórios devem ser validados
- Tratar excessões

**O que vamos avaliar?**

- Logica
- Boas praticas
- Se seu codigo está organizado

## Nivel 2:

Construa um CRUD que me permita gerenciar uma plataforma de e-commerce que possui clientes, produtos e pedidos.

**Requisitos**

- Seguir padrões Clean Architecture
- Campos obrigatórios devem ser validados
- Apenas clientes autenticados podem realizar pedidos
- Usar docker e docker-compose
- Testes e2e
- Tratar excessões
- Utilizar corretamente codigos de retorno. (404, 401...)

**O que vamos avaliar?**

- Documentação
- Boas praticas
- Segurança
- Commits

## Nivel 3:

Construa um CRUD que me permita gerenciar uma plataforma de e-commerce que possua clientes, produtos e pedidos.

Deve ser possivel para um administrador gerenciar a plataforma.

**Regras**

- Deve existir apenas um Administrador geral.
- Apenas administrador pode cadastrar usuarios para gerenciar a plataforma
- Campos obrigatórios devem ser validados
- Apenas clientes autenticados podem realizar pedidos
- Clientes não podem ver outros clientes

**Requisitos**

- Seguir padrões Clean Architecture
- Usar docker e docker-compose
- Utilizar corretamente codigos de retorno. (404, 401...)
- Testes e2e
- Testes unitarios
- Tratar excessões

**O que vamos Avaliar?**

- Arquitetura do projeto
- Documentação
- Boas praticas
- Segurança
- Commits
- Cobertura de testes


