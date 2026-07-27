---
title: Replace()
second_title: Aspose.Slides para C++ Referência da API
description: Substitui todas as ocorrências de um valor por um novo valor em um Span.
type: docs
weight: 287
url: /pt/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) função


Substitui todas as ocorrências de um valor por um novo valor em um [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to modify in-place |
| oldValue | const T\& | The value to search for and replace |
| newValue | const T\& | The new value to replace oldValue with |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) função


Copia elementos da fonte para o destino, substituindo valores especificados durante a cópia.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The source [ReadOnlySpan](../../system/readonlyspan/) to copy from |
| destination | [Span](../../system/span/)\<T\>\& | The destination [Span](../../system/span/) to copy to |
| oldValue | const T\& | The value to search for and replace during copying |
| newValue | const T\& | The new value to replace oldValue with |

## Ver também

* Classe [Span](../../system/span/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)