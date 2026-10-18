# Regras do Claude (Vinicius)

Cópia versionada das regras de `C:\Users\Monica\.claude\CLAUDE.md`. O Claude Code lê o arquivo global; este aqui é a fonte para guardar histórico e levar para outras IAs. Ao mudar uma regra, mudar nos dois.

## graphify
- **graphify** (`~/.claude/skills/graphify/SKILL.md`) - any input to knowledge graph. Trigger: `/graphify`
When the user types `/graphify`, use the installed graphify skill or instructions before doing anything else.

## Cofre e ferramentas (2026-10-18)
- Cofre Obsidian: `C:\Users\Monica\Segundo Cérebro`. Contexto do toolkit, catálogo de ferramentas e protocolo de sessão: `03 Resources/Ferramentas/Vibe Coding Toolkit - fundação de projeto Next.js (instalado 2026-10-18).md` (ler quando o pedido envolver ferramentas, projeto novo ou o cofre).
- Economia de tokens sempre: Caveman e Ponytail ligados; `graphify query` antes de ler arquivos quando houver `graphify-out/`; avisar custo antes de rodadas longas.
- Toda sessão: usar o Graphify MCP (workspace `vinicius-s-workspace-55a89d`; repos `vinicius828228/claude-e-codex` (personalização; local em `C:\Users\Monica\Ferramentas\claude-personalizado`), `vinicius828228/dhomus-codex-backup-2026-09-23` e `vinicius828228/dhomus-experimento`) antes de ler código desses repos — `graphify_find`, `query_graph`, `graphify_callers`/`graphify_callees` em vez de abrir arquivos inteiros. Seguir também o protocolo de sessão da nota do toolkit acima.
- Se a primeira mensagem não disser o que a pessoa precisa, fazer uma pergunta curta; depois recomendar do catálogo só as ferramentas úteis e pedir ok antes de instalar algo novo.
- Projeto Next.js novo: copiar `C:\Users\Monica\Ferramentas\modelo-next` (ver nota acima).
