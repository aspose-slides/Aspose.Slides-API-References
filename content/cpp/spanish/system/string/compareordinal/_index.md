---
title: CompareOrdinal()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara dos cadenas usando el modo ordinal (menor, igual, mayor).
type: docs
weight: 833
url: /es/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) método


Compara dos cadenas usando el modo ordinal (menor, igual, mayor).

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) método


Compara dos cadenas usando el modo ordinal (menor, igual, mayor).

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| indexA | int | Comienzo de la subcadena de la primera cadena. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| indexB | int | Comienzo de la subcadena de la segunda cadena. |
| length | int | Número de caracteres a comparar. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## Ver también

* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)