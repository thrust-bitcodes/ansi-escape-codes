# ANSI Escape Codes
Biblioteca para auxiliar na manipulação de código de ESCAPE ANSI.

## Utilização

Instalar o módulo através do comando:

```bash
thrust install ansi-escape-codes
```

## Exemplo

```js
const escapeCodes = require('ansi-escape-codes');

const red = escapeCodes.make(escapeCodes.COLORS.RED);

console.log('Normal | ' + red('Red'));
```