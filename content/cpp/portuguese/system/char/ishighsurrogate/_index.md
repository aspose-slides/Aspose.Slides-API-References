---
title: IsHighSurrogate()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o caractere no índice especificado na string especificada é uma unidade de código substituta alta UTF-16.
type: docs
weight: 40
url: /pt/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) método

Determina se o caractere no índice especificado na string especificada é uma unidade de código substituta alta UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | Uma string |
| index | int | O índice na string especificada do caractere a ser testado |

### Valor de retorno

True se o caractere no índice especificado for uma unidade de código substituta alta UTF-16, caso contrário - false

## Char::IsHighSurrogate(const char_t *, int) método

Determina se o caractere no índice especificado no buffer de caracteres especificado é um substituto alto.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const char_t * | Ponteiro para o início do buffer de caracteres |
| idx | int | Um índice baseado em zero no buffer especificado do caractere a ser testado |

### Valor de retorno

True se o caractere no índice especificado for um substituto alto, caso contrário - false

## Char::IsHighSurrogate(char_t) método

Determina se o caractere especificado é um substituto alto.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | O caractere a ser testado |

### Valor de retorno

True se o caractere especificado for um substituto alto, caso contrário - false

## Ver também

* Classe [String](../../string/)
* Classe [Char](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)