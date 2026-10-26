---
title: EndsWith()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si un ReadOnlySpan<T> termina con un solo valor.
type: docs
weight: 131
url: /es/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

Determina si un ReadOnlySpan<T> termina con un solo valor.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the end of the span |

### Valor devuelto

true si el span termina con el valor, false en caso contrario

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Determina si un ReadOnlySpan<T> termina con otro ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Valor devuelto

true si el span termina con el span de valor, false en caso contrario

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Determina si un Span<T> termina con un ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Valor devuelto

true si el span termina con el span de valor, false en caso contrario

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Determina si un ReadOnlySpan<T> termina con un Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Valor devuelto

true si el span termina con el span de valor, false en caso contrario

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

Determina si un Span<T> termina con otro Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Valor devuelto

true si el span termina con el span de valor, false en caso contrario

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Determina si un ReadOnlySpan<char16_t> termina con el valor especificado usando StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to check for at the end of the span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### Valor devuelto

true si el span termina con el valor, false en caso contrario

## Véase también

* Enumeración [StringComparison](../../system/stringcomparison/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)