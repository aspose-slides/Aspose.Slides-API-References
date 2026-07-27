---
title: SequenceEqual()
second_title: Referência da API Aspose.Slides para C++
description: Determina se dois ReadOnlySpans contêm elementos idênticos na mesma ordem.
type: docs
weight: 326
url: /pt/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se dois ReadOnlySpans contêm elementos idênticos na mesma ordem.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O primeiro span a ser comparado |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O segundo span a ser comparado |

### Valor de retorno

true se spans têm o mesmo comprimento e todos os elementos são iguais, false caso contrário

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se um [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) contêm elementos idênticos na mesma ordem.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a ser comparado |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a ser comparado |

### Valor de retorno

true se spans têm o mesmo comprimento e todos os elementos são iguais, false caso contrário

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) função


Determina se dois ReadOnlySpans contêm elementos iguais usando um comparador personalizado.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |
| TComparer | O tipo do objeto comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O primeiro span a ser comparado |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O segundo span a ser comparado |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ponteiro inteligente para o objeto comparador usado na comparação de elementos |

### Valor de retorno

true se spans têm o mesmo comprimento e comparador considera todos os elementos iguais, false caso contrário

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) função


Determina se um [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) contêm elementos iguais usando um comparador personalizado.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |
| TComparer | O tipo do objeto comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a ser comparado |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a ser comparado |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ponteiro inteligente para o objeto comparador usado na comparação de elementos |

### Valor de retorno

true se spans têm o mesmo comprimento e comparador considera todos os elementos iguais, false caso contrário

## Veja também

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)