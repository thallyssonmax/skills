# Skills — biblioteca pessoal

Repositório **público** para compartilhar skills pessoais reutilizáveis no ChatGPT, Codex e em outros agentes compatíveis.

> Ainda não há skills publicadas aqui. A estrutura está preparada para crescimento, sem criar skills fictícias.

## Organização

```text
.
├── .agents/
│   └── skills/
│       ├── README.md             # Como adicionar skills futuras
│       └── <nome-da-skill>/       # Criar apenas quando existir
│           ├── SKILL.md
│           └── references/       # Opcional
├── chatgpt-project/
│   └── README.md                 # Contextos opcionais para Projetos do ChatGPT
└── README.md
```

## Adicionar uma skill futuramente

1. Escolher um nome curto em inglês, minúsculo e com hifens.
2. Criar `.agents/skills/<nome-da-skill>/SKILL.md` com frontmatter `name` e `description`, seguido das instruções.
3. Adicionar referências, scripts ou exemplos apenas quando necessários.
4. Se quiser utilizar a skill como fonte em um Projeto do ChatGPT, gerar `chatgpt-project/<nome-da-skill>-context.md`.
5. Testar, revisar informações confidenciais, fazer commit e publicar.

## Uso e privacidade

Este repositório é **público**: não incluir PRDs internos, credenciais, dados de clientes, informações de projetos privados ou metodologias restritas.

Skills específicas para Frenet ficam exclusivamente no repositório **privado** `thallyssonmax/frenet-skills`, que NÃO deve ser copiado para cá.
