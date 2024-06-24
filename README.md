# DataX

Este projeto é um terminal de consulta para atender às necessidades de uma distribuidora de água de pequeno porte.

## Funcionalidades

### Autenticação

- [ ] Deve ser possível criar uma conta;
- [ ] Deve ser possível se autenticar usando e-mail e senha;
- [ ] Deve ser possível recuperar a senha usando o e-mail;

### Lojas

- [ ] Deve ser possível criar uma nova loja;
- [ ] Deve ser possível atualizar uma loja;
- [ ] Deve ser possível encerrar uma loja;

### Colaboradores

- [ ] Deve ser possível obter os colaboradores da loja;
- [ ] Deve ser possível atualizar o cargo de um colaborador;

### Convites

- [ ] Deve ser possível convidar colaboradores;
- [ ] Deve ser possível aceitar um convite;
- [ ] Deve ser possível rejeitar um convite;
- [ ] Deve ser possível revogar um convite pendente;

### Produtos

- [ ] Deve ser possível cadastrar um novo produto;
- [ ] Deve ser possível obter os produtos de uma loja;
- [ ] Deve ser possível atualizar um produto;
- [ ] Deve ser possível deletar um produto;

## RBAC

Cargos e permissões

### Cargos

Dono
Gerente
Colaborador

### Tabela de permissões

|                                  | Dono | Gerente | Colaborador|
|----------------------------------|------|---------|------------|
| Criar uma loja                   | ✅   | ❌      | ❌          |
| Atualizar uma loja               | ✅   | ✅      | ❌          |
| Encerrar uma loja                | ✅   | ❌      | ❌          |
| Atualizar o cargo do colaborador | ✅   | ❌      | ❌          |
| Convidar colaboradores           | ✅   | ✅      | ❌          |
| Revogar convite pendente         | ✅   | ✅      | ❌          |
| Cadastrar novo produto           | ✅   | ✅      | ❌          |
| Atualizar um produto             | ✅   | ✅      | ❌          |
| Deletar um produto               | ✅   | ✅      | ❌          |
|                                  |      |         |            |

> ✅ = permitido
> ❌ = não permitido
> ⚠️ = permitido com condições

### Condições
