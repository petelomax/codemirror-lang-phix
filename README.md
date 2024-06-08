# codemirror-lang-phix

A CodeMirror 6 mode for Phix.

## History

- This repo was forked from https://github.com/sachinraja/codemirror-lang-elixir, which was archived.
- Most of the code is from [codemirror-mode-elixir](https://github.com/ianwalter/codemirror-mode-elixir), which was not compatible with v6.
- Then quickly updated to phix by petelomax, with no testing or any attempt at packaging.

## Installation
```shell
npm install codemirror-lang-phix @codemirror/language
```

## Usage
Treat it the same way as a [legacy-modes](https://github.com/codemirror/legacy-modes) import:
```js
import { StreamLanguage } from '@codemirror/language'
import { phix } from 'codemirror-lang-phix'

const lang = StreamLanguage.define(phix)
```
