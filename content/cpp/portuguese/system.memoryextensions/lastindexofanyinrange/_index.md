---
title: LastIndexOfAnyInRange()
second_title: Referência da API Aspose.Slides para C++
description: Encontra a última ocorrência de qualquer elemento dentro do intervalo especificado em um span.
type: docs
weight: 261
url: /pt/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função

Encontra a última ocorrência de qualquer elemento dentro do intervalo especificado dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde a busca será feita |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do último elemento dentro do intervalo, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) função

Encontra a última ocorrência de qualquer elemento dentro do intervalo especificado dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde a busca será feita |
| lowInclusive | const T\& | O limite inferior do intervalo (inclusivo) |
| highInclusive | const T\& | O limite superior do intervalo (inclusivo) |

### Valor de retorno

O índice baseado em zero do último elemento dentro do intervalo, ou -1 se não encontrado

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)