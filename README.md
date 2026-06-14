# crowdsec stack module

- Module id: `crowdsec`
- Module repo: `crowdsec-stack-module`
- Source repo: none declared
- Lifecycle: `active`

## Owned overlays
- `stack.compose/crowdsec.yml`
- `stack.config/crowdsec`

## Dependencies
- `stack-foundation`

## Validation

```sh
./tests/validate.sh
```

## Lifecycle

`active` modules are expected to keep `stack.module.json`, owned overlays, and `tests/validate.sh` in sync.
