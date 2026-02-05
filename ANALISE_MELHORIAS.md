# O que eu mudaria neste projeto

No estado atual, este repositório está praticamente vazio (apenas `.gitkeep`).

## Mudanças prioritárias

1. **Adicionar estrutura base do projeto**
   - Linguagem/framework escolhido.
   - Estrutura de pastas (`src/`, `tests/`, `docs/`).

2. **Adicionar documentação mínima**
   - `README.md` com objetivo, setup e como executar.
   - Guia de contribuição (`CONTRIBUTING.md`).

3. **Configurar qualidade de código**
   - Lint/formatter (ex.: ESLint+Prettier, Ruff+Black, etc.).
   - Pipeline de CI para validar build e testes.

4. **Criar testes básicos**
   - Pelo menos um teste de fumaça para garantir execução inicial.

5. **Padronizar versionamento**
   - Estratégia de branches e commits semânticos.

## Próximo passo recomendado

Definir stack (ex.: React, Node, Python, etc.) e eu posso gerar a base completa com scripts de execução e testes.

## Como ver as alterações

Se você quer inspecionar alterações no Git, estes comandos cobrem o fluxo principal:

- Ver arquivos modificados e estado atual:
  - `git status`
- Ver diferenças ainda não commitadas (working tree):
  - `git diff`
- Ver diferenças já adicionadas com `git add` (staging):
  - `git diff --staged`
- Ver mudanças de um commit específico:
  - `git show <hash_do_commit>`
- Ver histórico resumido com commits:
  - `git log --oneline --decorate --graph`
- Comparar branch atual com `main`:
  - `git diff main...HEAD`

Exemplo para este repositório agora:

- `git log --oneline -n 5`
- `git show --name-only --stat HEAD`
