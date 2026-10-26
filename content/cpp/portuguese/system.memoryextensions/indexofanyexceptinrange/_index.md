---
title: IndexOfAnyExceptInRange()
second_title: Referência da API Aspose.Slides para C++
description: Encontra o índice do primeiro elemento que está fora do intervalo especificado em um ReadOnlySpan<T>
type: docs
weight: 183
url: /pt/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Encontra o índice do primeiro elemento que está fora do intervalo especificado em um ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de Retorno

O índice baseado em zero do primeiro elemento fora do intervalo, ou -1 se não encontrado

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function


Encontra o índice do primeiro elemento que está fora do intervalo especificado em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde pesquisar |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de Retorno

O índice baseado em zero do primeiro elemento fora do intervalo, ou -1 se não encontrado

## Veja Também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)