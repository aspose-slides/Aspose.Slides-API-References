---
title: ConvertToUtf32()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el par surrogate UTF-16 especificado en una unidad de código UTF-32.
type: docs
weight: 287
url: /es/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) método


Convierte el par surrogate UTF-16 especificado en una unidad de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| highSurrogate | char_t | El surrogate alto del par surrogate UTF-16 que se convertirá |
| lowSurrogate | char_t | El surrogate bajo del par surrogate UTF-16 que se convertirá |

### Valor de retorno

Una unidad de código UTF-32 resultante de la conversión

## Char::ConvertToUtf32(const String\&, int) método


Convierte el valor de un carácter codificado en UTF-16 o un par surrogate en una posición especificada de una cadena en una unidad de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | Una cadena que contiene un carácter o un par surrogate |
| index | int | La posición índice del carácter o par surrogate en la cadena especificada |

### Valor de retorno

Una unidad de código UTF-32 resultante de la conversión

## Ver también

* Class [Char](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)