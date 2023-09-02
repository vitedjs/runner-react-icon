# package-name

## Install

### Run directly

```bash
npx package-name
```

### Install on system

```bash
npm i -g package-name
%binName%
```

### Install in project

```bash
npm i -D package-name
```

Add script entry:

```json
{
  "scripts": {
    "%binName%": "%binName%"
  }
}
```

Run:

```bash
npm run %binName%
```

## Options

### `--help`

Show help

### `--version`

Show version
