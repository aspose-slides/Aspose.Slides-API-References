---
title: LastIndexOfAnyExceptInRange()
second_title: Referência da API Aspose.Slides para C++
description: Encontra a última ocorrência de qualquer elemento fora do intervalo especificado dentro de um span.
type: docs
weight: 248
url: /pt/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Encontra a última ocorrência de qualquer elemento fora do intervalo especificado dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser pesquisado |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do último elemento fora do intervalo, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Encontra a última ocorrência de qualquer elemento fora do intervalo especificado dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span a ser pesquisado |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do último elemento fora do intervalo, ou -1 se não encontrado

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)