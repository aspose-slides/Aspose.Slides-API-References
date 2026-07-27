---
title: Replace()
second_title: Referencia API de Aspose.Slides para C++
description: Reemplaza todas las apariciones de un valor con un nuevo valor en un Span.
type: docs
weight: 287
url: /es/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) función

Reemplaza todas las apariciones de un valor con un nuevo valor en un [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span a modificar in situ |
| oldValue | const T\& | El valor a buscar y reemplazar |
| newValue | const T\& | El nuevo valor con el que reemplazar oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) función

Copia elementos de la fuente al destino, reemplazando los valores especificados durante la copia.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) de origen del que copiar |
| destination | [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) de destino al que copiar |
| oldValue | const T\& | El valor a buscar y reemplazar durante la copia |
| newValue | const T\& | El nuevo valor con el que reemplazar oldValue |

## Ver también

* Clase [Span](../../system/span/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)