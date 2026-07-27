---
title: Contains()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica si un span de solo lectura contiene un valor específico.
type: docs
weight: 40
url: /es/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) función

Verifica si un span de solo lectura contiene un valor específico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a buscar |

### Valor de retorno

true si el valor se encuentra en el span, false de lo contrario

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) función

Verifica si un span mutable contiene un valor específico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value | const T\& | El valor a buscar |

### Valor de retorno

true si el valor se encuentra en el span, false de lo contrario

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) función

Verifica si un span de caracteres contiene otro span de caracteres con reglas de comparación especificadas.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span a buscar |
| comparisonType | [StringComparison](../../system/stringcomparison/) | El tipo de comparación de cadena a realizar |

### Valor de retorno

true si el valor se encuentra en el span, false de lo contrario

## Ver también

* Enumeración [StringComparison](../../system/stringcomparison/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)