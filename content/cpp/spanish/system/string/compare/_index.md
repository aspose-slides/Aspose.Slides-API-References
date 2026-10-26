---
title: Compare()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara dos subcadenas y devuelve un valor menor, igual o mayor.
type: docs
weight: 820
url: /es/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) método

Compara dos subcadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| indexA | int | Inicio de la subcadena de la primera cadena. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| indexB | int | Inicio de la subcadena de la segunda cadena. |
| length | int | Número de caracteres a comparar. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas/minúsculas. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) método

Compara dos subcadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| indexA | int | Inicio de la subcadena de la primera cadena. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| indexB | int | Inicio de la subcadena de la segunda cadena. |
| length | int | Número de caracteres a comparar. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas/minúsculas. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar para la comparación. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::Compare(const String\&, const String\&, System::StringComparison) método

Compara dos cadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) método

Compara dos cadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| indexA | int | Inicio de la subcadena de la primera cadena. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| indexB | int | Inicio de la subcadena de la segunda cadena. |
| length | int | Número de caracteres a comparar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::Compare(const String\&, const String\&, bool) método

Compara dos cadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas/minúsculas. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) método

Compara dos cadenas y devuelve un valor menor, igual o mayor.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas/minúsculas. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar para la comparación. |

### Valor devuelto

Valor negativo si la primera subcadena es menor que la segunda, cero si coinciden, valor positivo en caso contrario.

## Véase también

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)