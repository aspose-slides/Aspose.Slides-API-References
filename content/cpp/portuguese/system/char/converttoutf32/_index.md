---
title: ConvertToUtf32()
second_title: Referência da API Aspose.Slides para C++
description: Converte o par substituto UTF-16 especificado em unidade de código UTF-32.
type: docs
weight: 287
url: /pt/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) método

Converte o par substituto UTF-16 especificado em unidade de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| highSurrogate | char_t | O substituto alto do par substituto UTF-16 a ser convertido |
| lowSurrogate | char_t | O substituto baixo do par substituto UTF-16 a ser convertido |

### Valor de Retorno

Uma unidade de código UTF-32 resultante da conversão

## Char::ConvertToUtf32(const String\&, int) método

Converte o valor de um caractere codificado em UTF-16 ou par substituto em uma posição especificada em uma string em unidade de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | Uma string que contém um caractere ou par substituto |
| index | int | A posição de índice do caractere ou par substituto na string especificada |

### Valor de Retorno

Uma unidade de código UTF-32 resultante da conversão

## Veja também

* Classe [Char](../)
* Classe [String](../../string/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)