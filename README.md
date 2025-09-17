# @ei/biome

[![JSR](https://jsr.io/badges/@ei/biome)](https://jsr.io/@ei/biome)

> [!TIP]
> **Mantenedor**: @neves

Configuração padrão da E-Inscrição do [biome](https://biomejs.dev/) para todos os projetos js da empresa, front e back.

## Instalação

Executar na raiz do projeto:
```
bunx jsr add -D @ei/biome
```

Criar o arquivo [**biome.jsonc**](./biome.jsonc) na raiz do projeto.
```
wget https://raw.githubusercontent.com/raise-sistemas/jsr-biome/refs/heads/main/biome.jsonc
```

Testar no terminal:
```
biome check --reporter=summary
```

## Publicação

Este package é publicado no [JSR](https://jsr.io/@ei/biome) pelo comando:
```
bunx --bun jsr publish --verbose
```

Mas também é publicado automaticamente por um github workflow.
