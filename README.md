# 3 - Atividade Prática - Versionamento Semântico com Git e GitHub

## Tema: Agenda de Contatos

---

## Objetivo

Aprender e aplicar **versionamento semântico completo**, incluindo **commits padronizados**, **tags vinculadas a commits específicos** e **automação via GitHub Actions**, utilizando como exemplo o projeto **Agenda de Contatos**.

---

## Estrutura do Projeto

**Nome do repositório:** `agenda-contatos`

**Descrição:** Projeto prático de versionamento e automação contínua para uma aplicação de Agenda de Contatos.

**Funcionalidades principais:**

- `feature/contatos` → cadastro e listagem de contatos
- `feature/favoritos` → marcação e desmarcação de contatos favoritos

---

## Etapa 1 - Criar o Repositório

1. Crie o repositório no **GitHub** com o nome `agenda-contatos`.
2. Clone para o computador (repositório local).
3. Crie um arquivo inicial, como o “readme.md”, por exemplo.
4. Gere uma tag SemVer que contenha o hash do commit inicial.
5. Envie a tag criada ao repositório github.

---

## Etapa 2 - Desenvolver Funcionalidades

### Branch: `feature/contatos`

1. Crie e mude para a branch `feature/contatos.`
2. Crie um módulo / arquivo qualquer inicial pela branch `feature/contatos`. Exemplo:

   ```bash
   echo "função de cadastro e listagem de contatos" > contatos.txt
   ```

3. Adicione (git add) o arquivo e criado ao repositório e faça o commit semântico.
4. Verifique o hash do commit e crie uma tag vinculada.
5. Envie a tag criada ao repositório github.

---

### Branch: `feature/favoritos`

1. Crie e mude para a branch `feature/favoritos.`
2. Crie um módulo / arquivo qualquer inicial pela branch `feature/favoritos` Exemplo:

   ```bash
   echo "função de marcação de contatos favoritos" > favoritos.txt
   ```

3. Adicione (git add) o arquivo e criado ao repositório e faça o commit semântico.
4. Verifique o hash do commit e crie uma tag vinculada.

---

## Etapa 3 - Merge das Funcionalidades na `main`

1. Vá para a branch principal (main).
2. Faça merge das duas branches (`feature/contatos` e `feature/favoritos`) na main.
3. Gere um commit semântico dessa integração.
4. Copie o hash desse commit e crie uma tag SemVer vinculada.
5. Envie a tag criada ao repositório github.

---

## Entregar - Link do Repositório`agenda-contatos`

- O repositório `agenda-contatos` deve conter:
  - Branches:
    - `feature/contatos`
    - `feature/favoritos`
  - Commits semânticos (com escopos)
  - Tags vinculadas a hashes específicos

## Entrega da atividade

Por favor, entregue o link do repositório na tarefa postada na equipe do Microsoft Teams.

Se o repositório for privado, dar permissão para o usuário do professor **adrianoprof**

---

## Critérios de Avaliação

| Critério                   | Descrição                                               | Peso (%) |
| -------------------------- | ------------------------------------------------------- | -------- |
| Estrutura do repositório   | Organização inicial com readme                          | 25       |
| Commits semânticos         | Uso correto de `feat`, `fix`, `docs`, etc. com escopo   | 25       |
| Tags vinculadas            | Criação de tags associadas diretamente a commits (hash) | 25       |
| Merge e integração na main | Integração correta e coerente                           | 25       |
