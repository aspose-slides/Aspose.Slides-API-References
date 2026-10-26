---
title: IndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Búsqueda hacia adelante de subcadena.
type: docs
weight: 625
url: /es/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const método


Búsqueda hacia adelante de subcadena.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) del primer subcadena encontrado o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve 0.

## String::IndexOf(char_t, int) const método


Búsqueda hacia adelante de carácter.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Carácter a buscar. |
| startIndex | int | [Index](../../index/) para iniciar la búsqueda en. |

### Valor devuelto

[Index](../../index/) de la primera posición de carácter desde startIndex o -1 si no se encuentra.

## String::IndexOf(char_t, int, int) const método


Búsqueda hacia adelante de carácter en subcadena.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Carácter a buscar. |
| startIndex | int | [Index](../../index/) para iniciar la búsqueda en. |
| count | int | Número de caracteres a examinar. |

### Valor devuelto

[Index](../../index/) de la primera posición de carácter desde startIndex o -1 si no se encuentra.

## String::IndexOf(const String\&, int) const método


Búsqueda hacia adelante de subcadena.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena origen donde iniciar la búsqueda. |

### Valor devuelto

[Index](../../index/) del primer subcadena encontrado o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const método


Búsqueda hacia adelante de subcadena.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena origen donde iniciar la búsqueda. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) del primer subcadena encontrado o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const método


Búsqueda hacia adelante de subcadena.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena origen donde iniciar la búsqueda. |
| count | int | número de caracteres a examinar. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

[Index](../../index/) del primer subcadena encontrado o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve startIndex.

## String::IndexOf(const String\&, int, int) const método


Búsqueda hacia adelante de subcadena.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | Subcadena a buscar. |
| startIndex | int | Posición en la cadena origen donde iniciar la búsqueda. |
| count | int | número de caracteres a examinar. |

### Valor devuelto

[Index](../../index/) del primer subcadena encontrado o -1 si no se encuentra. Para una cadena de búsqueda vacía, siempre devuelve startIndex.

## Ver también

* Enumeración [StringComparison](../../stringcomparison/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)