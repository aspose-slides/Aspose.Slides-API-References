---
title: SequenceCompareTo()
second_title: Referência da API Aspose.Slides para C++
description: Compara dois ReadOnlySpans lexicograficamente.
type: docs
weight: 313
url: /pt/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função

Compara dois ReadOnlySpans lexicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A primeira span a comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A segunda span a comparar |

### Valor de retorno

- 1 se span < other, 0 se span == other, 1 se span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função

Compara um [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) lexicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a comparar |

### Valor de retorno

- 1 se span < other, 0 se span == other, 1 se span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) função

Compara um [ReadOnlySpan](../../system/readonlyspan/) e [Span](../../system/span/) lexicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a comparar |
| other | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a comparar |

### Valor de retorno

- 1 se span < other, 0 se span == other, 1 se span > other

## Veja Também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)