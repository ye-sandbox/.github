# ye-sandbox

Laboratório pessoal de [yegear1](https://github.com/yegear1) para templates de agentes, homelab e experimentos. O perfil principal fica reservado a projetos mais acabados; aqui as ideias nascem, quebram e viram padrão.

## Em foco agora

**Desenvolvimento com agentes.** O hub é [`template-agent`](https://github.com/ye-sandbox/template-agent): starters e governança (ADD) para Cursor, Claude Code, Antigravity e similares. Branches por tipo de trabalho — `greenfield`, `brownfield`, `blackbox` e `infra` — em vez de um monorepo inchado.

**Observabilidade no homelab.** [`infra-victoria-logs`](https://github.com/ye-sandbox/infra-victoria-logs) empilha VictoriaLogs + Vector para Proxmox e Docker, com API/MCP pensada para humanos e para agentes diagnosticarem incidentes.

Há também repositórios privados de integração com sistemas fechados, automação e instalação de serviços. Esses não aparecem no perfil público.

## Repositórios públicos

| Repositório | O que é |
| --- | --- |
| [template-agent](https://github.com/ye-sandbox/template-agent) | Hub de templates e regras para Agent-Driven Development |
| [infra-victoria-logs](https://github.com/ye-sandbox/infra-victoria-logs) | Stack mínima de logs (VictoriaLogs + Vector) para mini-PC / Proxmox |
| [ts-svelte-learning](https://github.com/ye-sandbox/ts-svelte-learning) | Estudo de Svelte 5, SvelteKit, runes e rotas |
| [py-importlib-learning](https://github.com/ye-sandbox/py-importlib-learning) | Experimentos com `importlib` e carregamento dinâmico em Python |

## Convenção de nomes

| Prefixo | Uso |
| --- | --- |
| `template-*` | Starters e governança para agentes |
| `infra-*` | Compose, Proxmox, homelab, instalação de serviços |
| `py-*` | Python (APIs, scrapers, estudo de libs) |
| `ts-*` | TypeScript / Svelte / front-end |

Projetos de estudo ou PoC sem destino claro continuam nesta org. Quando estabilizam, o destino é o perfil [yegear1](https://github.com/yegear1) ou um repositório de produto.
