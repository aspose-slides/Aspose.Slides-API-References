---
title: LastIndexOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Búsqueda inversa de subcadena.
type: docs
weight: 651
url: /es/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method

Búsqueda inversa de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena de origen donde comenzar la búsqueda. |

### Valor devuelto

[Index](../../index/) de la última subcadena encontrada o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve la longitud de la cadena.

## String::LastIndexOf(const String\&, System::StringComparison) const method

Búsqueda inversa de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) de la última subcadena encontrada o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve la longitud de la cadena.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method

Búsqueda inversa de subcadena.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena de origen donde comenzar la búsqueda. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) de la última subcadena encontrada o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve la longitud de la cadena.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method

Búsqueda inversa de subcadena.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena de origen donde comenzar la búsqueda. |
| count | int | Número de caracteres a examinar. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) de la última subcadena encontrada o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve startIndex+count.

## String::LastIndexOf(char_t) const method

Búsqueda inversa de carácter.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | Carácter a buscar. |

### Valor devuelto

[Index](../../index/) de la última posición del carácter o -1 si no se encuentra.

## String::LastIndexOf(char_t, int32_t) const method

Búsqueda inversa de carácter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | Carácter a buscar. |
| startIndex | **int32_t** | [Index](../../index/) para iniciar la búsqueda en. |

### Valor devuelto

[Index](../../index/) de la última posición del carácter desde startIndex o -1 si no se encuentra.

## String::LastIndexOf(char_t, int32_t, int32_t) const method

Búsqueda inversa de carácter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | Carácter a buscar. |
| startIndex | **int32_t** | [Index](../../index/) para iniciar la búsqueda en. |
| count | **int32_t** | Número de caracteres a examinar |
 
### Valor devuelto

[Index](../../index/) de la última posición del carácter desde startIndex o -1 si no se encuentra.

## Ver también

* Enum [StringComparison](../../stringcomparison/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)