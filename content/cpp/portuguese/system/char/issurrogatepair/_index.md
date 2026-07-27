---
title: IsSurrogatePair()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se os dois caracteres especificados formam um par substituto UTF-16.
type: docs
weight: 27
url: /pt/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method

Determina se os dois caracteres especificados formam um par substituto UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| highSurrogate | char_t | Um caractere que é testado para ser um substituto alto |
| lowSurrogate | char_t | Um caractere que é testado para ser um substituto baixo |

### Valor de Retorno

True se os caracteres especificados formarem um par substituto, caso contrário - false

## Char::IsSurrogatePair(const String\&, int) method

Determina se dois caracteres consecutivos no buffer de caracteres especificado formam um par substituto.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../string/)\& | Uma string |
| index | int | Um índice baseado em zero no buffer especificado onde a sequência de caracteres a ser testada começa |

### Valor de Retorno

True se os caracteres especificados formarem um par substituto, caso contrário - false

## Ver Também

* Classe [Char](../)
* Classe [String](../../string/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)