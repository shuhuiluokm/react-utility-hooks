# react-utility-hooks

Small typed hooks: debounce, localStorage, media query, toggle

Started as a weekend hack, grew on me.

## Highlights

- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React
- useDebounce with leading/trailing options

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Installation

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── package.json
```

## Development

```bash
npm install
```

## 说明

个人练习项目, 谨慎用于生产环境。
