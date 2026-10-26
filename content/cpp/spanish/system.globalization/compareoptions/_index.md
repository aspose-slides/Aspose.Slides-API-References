---
title: CompareOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Opciones de comparación de cadenas.
type: docs
weight: 430
url: /es/system.globalization/compareoptions/
---
## CompareOptions enum

[String](../../system/string/) opciones de comparación.

```cpp
enum class CompareOptions : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Sin opciones especiales. |
| IgnoreCase | 1 | Ignorar mayúsculas y minúsculas. |
| IgnoreNonSpace | 2 | Ignorar caracteres combinados sin espacio, p. ej. diacríticos. |
| IgnoreSymbols | 4 | Incluir espacios en blanco, signos de puntuación, etc. |
| IgnoreKanaType | 8 | Ignorar tipo kana (japonés). |
| IgnoreWidth | 16 | Ignorar ancho de carácter al comparar cadenas. |
| OrdinalIgnoreCase | 268435456 | Comparación ordinal con diferencias de mayúsculas ignoradas. |
| StringSort | 536870912 | Usar algoritmo de ordenamiento de cadenas para comparar caracteres. |
| Ordinal | 1073741824 | Comparar códigos UTF directamente para la primera comparación. |

## Ver también

* Espacio de nombres [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)