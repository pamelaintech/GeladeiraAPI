# Geladeira API

API desenvolvida em ASP.NET Core com foco em boas práticas de arquitetura, aplicando os princípios de SOLID e separação de responsabilidades.  
O projeto simula o gerenciamento de itens em uma geladeira, permitindo operações de CRUD com validações de negócio.

## Funcionalidades
- Cadastro de itens
- Consulta de itens
- Atualização de informações
- Remoção de itens
- Validação de regras de negócio (ex: posições vazias, organização dos itens)

## Arquitetura e Boas Práticas
- Arquitetura em camadas (Controller, Service, Repository)
- Princípios SOLID
- Injeção de Dependência nativa do ASP.NET Core
- Separação de regras de negócio e acesso a dados

## Tecnologias Utilizadas
- C#
- ASP.NET Core
- Entity Framework Core
- ADO.NET
- SQL Server
- xUnit e Moq (testes unitários)
- Git

## Banco de Dados
O projeto utiliza:
- Entity Framework Core para ORM
- ADO.NET para consultas diretas em cenários específicos

### Migrações
```bash
Add-Migration Inicial
Update-Database
