# 📦 Pokédex Mentor Pack

Este pacote prepara Antigravity, OpenCode ou outro agente de código para construir uma Pokédex **junto com o aluno**, no modo mentor.

## Arquivos

### `AGENTS.md`

Entrada curta e operacional para o agente.

Define:

- papel do tutor;
- anti-autopilot;
- ordem de leitura;
- primeira interação;
- regras de API;
- regras de wireframe;
- validação.

### `POKEDEX_MENTOR_PROTOCOL.md`

Protocolo pedagógico específico da Pokédex.

Aprofunda:

- HTTP;
- DTO/View Model;
- N+1;
- Signals/RxJS;
- busca;
- filtros;
- paginação;
- rotas;
- acessibilidade;
- testes;
- debugging;
- performance.

### `DESAFIO_02_POKEDEX_ANGULAR22_MENTOR.md`

Currículo completo do desafio.

Contém:

- requisitos;
- fases;
- wireframes;
- decisões;
- critérios de aceite;
- checkpoints;
- quiz;
- Definition of Done.

### `MENTORIA_STATE.md`

Memória operacional do projeto.

O mentor deve atualizá-la à medida que escolhas e evidências surgirem.

## Como usar

1. Coloque os quatro arquivos na raiz do projeto/repositório.
2. Abra o projeto no Antigravity ou OpenCode.
3. Diga ao agente:

```text
Leia AGENTS.md e siga o Mentor Mode.
Não implemente nada antes de executar a primeira interação definida nos arquivos.
Quero construir a Pokédex junto com você, etapa por etapa.
```

4. Responda às decisões uma por vez.
5. Não aceite que o agente pule validações ou wireframes.

## Observação sobre a API

O desafio usa **PokéAPI** (`https://pokeapi.co/api/v2/`).

Ela é uma API pública/comunitária para dados de Pokémon e não deve ser descrita como API oficial da The Pokémon Company.
