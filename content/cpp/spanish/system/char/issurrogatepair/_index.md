---
title: IsSurrogatePair()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si los dos caracteres especificados forman un par sustituto UTF-16.
type: docs
weight: 27
url: /es/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) método

Determina si los dos caracteres especificados forman un par sustituto UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| highSurrogate | char_t | A character that is tested for being a high surrogate |
| lowSurrogate | char_t | A character that is tested for being a low surrogate |

### Valor de retorno

True si los caracteres especificados forman un par sustituto, de lo contrario - false

## Char::IsSurrogatePair(const String\&, int) método

Determina si dos caracteres consecutivos en el búfer de caracteres especificado forman un par sustituto.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../string/)\& | A string |
| index | int | A zero based index in the specified buffer at which the character sequence to test begins |

### Valor de retorno

True si los caracteres especificados forman un par sustituto, de lo contrario - false

## Ver también

* Clase [Char](../)
* Clase [String](../../string/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)