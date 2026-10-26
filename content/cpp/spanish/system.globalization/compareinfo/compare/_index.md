---
title: Compare()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara cadenas. No implementado.
type: docs
weight: 66
url: /es/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const método

Compara cadenas. No implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Cadena LHS. |
| string2 | const [String](../../../system/string/)\& | Cadena RHS. |

### Valor devuelto

Valor negativo si la cadena LHS precede a la cadena RHS, cero si coinciden, valor positivo en otro caso.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const método

Compara cadenas. Sólo los modos Ordinal y OrdinalIgnoreCase son compatibles.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Cadena LHS. |
| b | const [String](../../../system/string/)\& | Cadena RHS. |
| options | [CompareOptions](../../compareoptions/) | Tipo de comparación [String](../../../system/string/). |

### Valor devuelto

Valor negativo si la cadena LHS precede a la cadena RHS, cero si coinciden, valor positivo en otro caso.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const método

Compara una sección de una cadena con una sección de la segunda cadena. No implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primera cadena. |
| offset1 | int | Índice inicial de los caracteres en **string1**. |
| length1 | int | Número de caracteres en **string1** a comparar. |
| string2 | const [String](../../../system/string/)\& | Segunda cadena. |
| offset2 | int | Índice inicial de los caracteres en **string2**. |
| length2 | int | Número de caracteres en **string2** a comparar. |

### Valor devuelto

Valor negativo si la sección de la primera cadena precede a la sección de la segunda cadena, cero si coinciden, valor positivo en otro caso.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const método

Compara la sección final de una cadena con la sección final de la segunda cadena usando métodos de comparación de cadenas. No implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primera cadena. |
| offset1 | int | Índice inicial de los caracteres en **string1**. |
| string2 | const [String](../../../system/string/)\& | Segunda cadena. |
| offset2 | int | Índice inicial de los caracteres en **string2**. |
| options | [CompareOptions](../../compareoptions/) | Opciones de comparación [String](../../../system/string/). |

### Valor devuelto

Valor negativo si la sección de la primera cadena precede a la sección de la segunda cadena, cero si coinciden, valor positivo en otro caso.

## CompareInfo::Compare(const String\&, int, const String\&, int) const método

Compara la sección final de una cadena con la sección final de la segunda cadena. No implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primera cadena. |
| offset1 | int | Índice inicial de los caracteres en **string1**. |
| string2 | const [String](../../../system/string/)\& | Segunda cadena. |
| offset2 | int | Índice inicial de los caracteres en **string2**. |

### Valor devuelto

Valor negativo si la sección de la primera cadena precede a la sección de la segunda cadena, cero si coinciden, valor positivo en otro caso.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const método

Compara una sección de una cadena con una sección de la segunda cadena usando métodos de comparación de cadenas. No implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primera cadena. |
| offset1 | int | Índice inicial de los caracteres en **string1**. |
| length1 | int | Número de caracteres en **string1** a comparar. |
| string2 | const [String](../../../system/string/)\& | Segunda cadena. |
| offset2 | int | Índice inicial de los caracteres en **string2**. |
| length2 | int | Número de caracteres en **string2** a comparar. |
| options | [CompareOptions](../../compareoptions/) | Opciones de comparación [String](../../../system/string/). |

### Valor devuelto

Valor negativo si la sección de la primera cadena precede a la sección de la segunda cadena, cero si coinciden, valor positivo en otro caso.

## Véase también

* Enumeración [CompareOptions](../../compareoptions/)
* Clase [String](../../../system/string/)
* Clase [CompareInfo](../)
* Espacio de nombres [System::Globalization](../../)
* Biblioteca [Aspose.Slides](../../../)