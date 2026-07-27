---
title: GetNumericValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el valor numérico asociado al carácter especificado.
type: docs
weight: 27
url: /es/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) método

Obtiene el valor numérico asociado al carácter especificado.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | char16_t | Carácter Unicode. |

### Valor devuelto

El valor numérico o -1 si el carácter especificado no es un carácter numérico.

## CharUnicodeInfo::GetNumericValue(const String\&, int) método

Obtiene el valor numérico asociado al carácter en el índice especificado de la cadena.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La cadena que contiene el carácter Unicode. |
| index | int | El índice del carácter Unicode. |

### Valor devuelto

El valor numérico o -1 si el carácter especificado no es un carácter numérico.

## Ver también

* Clase [CharUnicodeInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Globalization](../../)
* Biblioteca [Aspose.Slides](../../../)