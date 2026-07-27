---
title: BinarySearch()
second_title: Aspose.Slides para C++ Referência de API
description: Executa busca binária em um span classificado.
type: docs
weight: 14
url: /pt/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) função

Executa busca binária em um span classificado.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |
| TComparable | O tipo do valor comparável |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span classificado a ser pesquisado |
| comparable | const TComparable\& | O valor a ser pesquisado |

### Valor de retorno

[Index](../../system/index/) do elemento encontrado, ou complemento bit a bit do ponto de inserção se não encontrado

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) função

Executa busca binária em um span classificado usando um comparador personalizado.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |
| TComparer | O tipo do comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span classificado a ser pesquisado |
| value | const T\& | O valor a ser pesquisado |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | O comparador a ser usado para comparações |

### Valor de retorno

[Index](../../system/index/) do elemento encontrado, ou complemento bit a bit do ponto de inserção se não encontrado

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) função

Executa busca binária em um span classificado mutável.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |
| TComparable | O tipo do valor comparável |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span classificado a ser pesquisado |
| comparable | const TComparable\& | O valor a ser pesquisado |

### Valor de retorno

[Index](../../system/index/) do elemento encontrado, ou complemento bit a bit do ponto de inserção se não encontrado

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) função

Executa busca binária em um span classificado mutável usando um comparador personalizado.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |
| TComparer | O tipo do comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span classificado a ser pesquisado |
| value | const T\& | O valor a ser pesquisado |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | O comparador a ser usado para comparações |

### Valor de retorno

[Index](../../system/index/) do elemento encontrado, ou complemento bit a bit do ponto de inserção se não encontrado

## Veja também

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)