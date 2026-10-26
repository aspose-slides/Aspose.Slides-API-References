---
title: CommonPrefixLength()
second_title: Aspose.Slides para C++ Referência da API
description: Encontra o comprimento do prefixo comum entre duas spans.
type: docs
weight: 27
url: /pt/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra o comprimento do prefixo comum entre duas spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A primeira span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A segunda span |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra o comprimento do prefixo comum entre uma span mutável e uma span somente leitura.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span mutável |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span somente leitura |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) função


Encontra o comprimento do prefixo comum entre duas spans mutáveis.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A primeira span mutável |
| other | const [Span](../../system/span/)\<T\>\& | A segunda span mutável |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) função


Encontra o comprimento do prefixo comum entre duas spans usando um comparador de igualdade personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |
| TEqualityComparer | O tipo do comparador de igualdade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A primeira span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A segunda span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | O comparador de igualdade a ser usado para comparação de elementos |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) função


Encontra o comprimento do prefixo comum entre uma span mutável e uma span somente leitura usando um comparador de igualdade personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |
| TEqualityComparer | O tipo do comparador de igualdade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span mutável |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span somente leitura |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | O comparador de igualdade a ser usado para comparação de elementos |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) função


Encontra o comprimento do prefixo comum entre duas spans mutáveis usando um comparador de igualdade personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |
| TEqualityComparer | O tipo do comparador de igualdade |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A primeira span mutável |
| other | const [Span](../../system/span/)\<T\>\& | A segunda span mutável |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | O comparador de igualdade a ser usado para comparação de elementos |

### Valor de Retorno

O número de elementos correspondentes no início de ambas as spans

## Veja Também

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)