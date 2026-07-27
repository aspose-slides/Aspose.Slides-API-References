---
title: Sort()
second_title: Referência da API Aspose.Slides para C++
description: Ordena um Span usando um comparador personalizado.
type: docs
weight: 339
url: /pt/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) função


Ordena um [Span](../../system/span/) usando um comparador personalizado.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |
| TComparer | O tipo do objeto comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span a ser ordenado |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ponteiro inteligente para o objeto comparador usado na comparação dos elementos |

## System::MemoryExtensions::Sort(Span\<T\>\&) função


Ordena um [Span](../../system/span/) usando a comparação padrão.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | O span a ser ordenado |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) função


Ordena pares chave-valor usando um comparador personalizado (chaves e valores ordenados juntos)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |
| TComparer | O tipo do objeto comparador |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves a ser ordenado |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores a ser ordenado (mantendo correspondência com as chaves) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ponteiro inteligente para o objeto comparador usado na comparação das chaves |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) função


Ordena pares chave-valor usando um delegado de comparação.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves a ser ordenado |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores a ser ordenado |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | Delegado [Comparison](../../system/comparison/) para comparação das chaves |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) função


Ordena pares chave-valor usando a comparação padrão.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo das chaves |
| TValue | O tipo dos valores |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | O span de chaves a ser ordenado |
| values | [Span](../../system/span/)\<TValue\>\& | O span de valores a ser ordenado |

## Veja Também

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [Span](../../system/span/)
* Classe [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)