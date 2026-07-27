---
title: ContainsAnyExceptInRange()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se um span somente leitura contém algum elemento fora do intervalo especificado.
type: docs
weight: 79
url: /pt/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função

Verifica se um span somente leitura contém algum elemento fora do intervalo especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span (deve ser comparável) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde buscar |
| lowInclusive | const T\& | O limite inferior (inclusivo) |
| highInclusive | const T\& | O limite superior (inclusivo) |

### Valor de retorno

true se algum elemento fora do intervalo for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) função

Verifica se um span mutável contém algum elemento fora do intervalo especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span (deve ser comparável) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde buscar |
| lowInclusive | const T\& | O limite inferior (inclusivo) |
| highInclusive | const T\& | O limite superior (inclusivo) |

### Valor de retorno

true se algum elemento fora do intervalo for encontrado, false caso contrário

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)