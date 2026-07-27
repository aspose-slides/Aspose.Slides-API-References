---
title: StartsWith()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si el span comienza con el valor especificado.
type: docs
weight: 352
url: /es/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) función


Comprueba si el span comienza con el value especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the beginning of the span |

### Valor devuelto

true si el span comienza con el value, false de lo contrario

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función


Comprueba si el span comienza con el span de valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to check for at the beginning |

### Valor devuelto

true si el span comienza con el value span, false de lo contrario

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Comprueba si el span mutable comienza con el span de valor de solo lectura especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span containing values to check for |

### Valor devuelto

true si el span comienza con el value span, false de lo contrario

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) función


Comprueba si el span de solo lectura comienza con el span mutable especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span to check |
| value | const [Span](../../system/span/)\<T\>\& | The mutable span containing values to check for |

### Valor devuelto

true si el span comienza con el value span, false de lo contrario

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) función


Comprueba si el span de caracteres comienza con el span de valor especificado usando comparación de cadenas.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span containing values to check for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Valor devuelto

true si el span comienza con el value span, false de lo contrario

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) función


Comprueba si un span de cadenas comienza con la matriz de caracteres especificada.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | The string span to check |
| val | const char16_t * | The character array to check for at the beginning |

### Valor devuelto

true si el span comienza con el character array, false de lo contrario

## Véase también

* Enumeración [StringComparison](../../system/stringcomparison/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Clase [String](../../system/string/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)