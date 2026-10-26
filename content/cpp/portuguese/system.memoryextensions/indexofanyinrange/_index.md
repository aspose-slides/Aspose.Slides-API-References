---
title: IndexOfAnyInRange()
second_title: Referência da API Aspose.Slides para C++
description: Encontra o índice do primeiro elemento que está dentro do intervalo especificado em um ReadOnlySpan<T>
type: docs
weight: 196
url: /pt/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função


Encontra o índice do primeiro elemento que está dentro do intervalo especificado em um ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser pesquisado |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do primeiro elemento dentro do intervalo, ou -1 se não encontrado

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) função


Encontra o índice do primeiro elemento que está dentro do intervalo especificado em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span a ser pesquisado |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do primeiro elemento dentro do intervalo, ou -1 se não encontrado

## Veja Também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)