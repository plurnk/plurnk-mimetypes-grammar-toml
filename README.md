# @plurnk/plurnk-mimetypes-grammar-toml

Pre-built `tree-sitter-toml` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-toml
```

## what's in here

- **`toml.wasm`** — pre-built from the pinned upstream [tree-sitter-toml](https://github.com/tree-sitter-grammars/tree-sitter-toml) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `toml.wasm` is built from the upstream tree-sitter-toml grammar; see the pinned commit for that project's attribution.
