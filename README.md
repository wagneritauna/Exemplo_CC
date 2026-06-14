# Exemplo_CC

Projeto de exemplo para treinamento e exploração do **Claude Code** — a CLI oficial da Anthropic para interação com Claude diretamente no terminal e IDEs.

## Sobre o Projeto

Este repositório foi criado como ambiente de estudo e experimentação com o Claude Code, documentando casos de uso práticos, fluxos de trabalho e boas práticas para uso da ferramenta no dia a dia do desenvolvimento de software.

## O que é o Claude Code?

O **Claude Code** é a CLI da Anthropic que permite:

- Interagir com o Claude diretamente no terminal
- Editar, refatorar e revisar código com assistência de IA
- Executar tarefas complexas de engenharia de software de ponta a ponta
- Integrar-se com IDEs como VS Code e JetBrains
- Gerenciar servidores MCP (Model Context Protocol)
- Automatizar tarefas via hooks e agendamentos

## Estrutura

```
Exemplo_CC/
└── README.md
```

## Como Usar o Claude Code

### Instalação

```bash
npm install -g @anthropic-ai/claude-code
```

### Iniciar

```bash
claude
```

### Comandos Úteis

| Comando | Descrição |
|---|---|
| `/help` | Exibe ajuda |
| `/clear` | Limpa o contexto da conversa |
| `/config` | Abre as configurações |
| `/code-review` | Revisa o diff atual |
| `/init` | Inicializa o CLAUDE.md do projeto |

## Recursos

- [Documentação Oficial do Claude Code](https://docs.anthropic.com/claude-code)
- [Claude API](https://docs.anthropic.com/api)
- [Repositório de Issues](https://github.com/anthropics/claude-code/issues)

## Autor

Wagner Itaúna — [@wagneritauna](https://github.com/wagneritauna)
