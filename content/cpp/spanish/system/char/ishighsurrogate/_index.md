---
title: IsHighSurrogate()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código de sustituto alto UTF-16.
type: docs
weight: 40
url: /es/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) método

Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código de sustituto alto UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | Una cadena |
| index | int | El índice en la cadena especificada del carácter a probar |

### Valor devuelto

Verdadero si el carácter en el índice especificado es una unidad de código de sustituto alto UTF-16, de lo contrario - falso

## Char::IsHighSurrogate(const char_t *, int) método

Determina si el carácter en el índice especificado del búfer de caracteres especificado es un sustituto alto.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char_t * | Puntero al comienzo del búfer de caracteres |
| idx | int | Un índice basado en cero en el búfer especificado del carácter a probar |

### Valor devuelto

Verdadero si el carácter en el índice especificado es un sustituto alto, de lo contrario - falso

## Char::IsHighSurrogate(char_t) método

Determina si el carácter especificado es un sustituto alto.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | El carácter a probar |

### Valor devuelto

Verdadero si el carácter especificado es un sustituto alto, de lo contrario - falso

## Ver también

* Clase [String](../../string/)
* Clase [Char](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)