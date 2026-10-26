---
title: LastIndexOfAny()
second_title: Aspose.Slides para C++ Referência da API
description: Encontra a última ocorrência de qualquer um dos três valores especificados dentro de um span.
type: docs
weight: 222
url: /pt/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) função


Encontra a última ocorrência de qualquer um dos três valores especificados dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde a pesquisa será feita |
| value0 | const T\& | O primeiro valor a ser pesquisado |
| value1 | const T\& | O segundo valor a ser pesquisado |
| value2 | const T\& | O terceiro valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) função


Encontra a última ocorrência de qualquer um dos três valores especificados dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde a pesquisa será feita |
| value0 | const T\& | O primeiro valor a ser pesquisado |
| value1 | const T\& | O segundo valor a ser pesquisado |
| value2 | const T\& | O terceiro valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função


Encontra a última ocorrência de qualquer um dos dois valores especificados dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde a pesquisa será feita |
| value0 | const T\& | O primeiro valor a ser pesquisado |
| value1 | const T\& | O segundo valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) função


Encontra a última ocorrência de qualquer um dos dois valores especificados dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde a pesquisa será feita |
| value0 | const T\& | O primeiro valor a ser pesquisado |
| value1 | const T\& | O segundo valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra a última ocorrência de qualquer valor de uma sequência dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde a pesquisa será feita |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A sequência de valores a ser pesquisada |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra a última ocorrência de qualquer valor de uma sequência dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde a pesquisa será feita |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A sequência de valores a ser pesquisada |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) função


Encontra a última ocorrência de qualquer valor de uma sequência mutável dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde a pesquisa será feita |
| values | const [Span](../../system/span/)\<T\>\& | A sequência de valores a ser pesquisada |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## Veja Também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)