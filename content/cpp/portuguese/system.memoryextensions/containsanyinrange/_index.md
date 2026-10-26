---
title: ContainsAnyInRange()
second_title: Aspose.Slides para C++ Referência da API
description: Verifica se um span somente leitura contém algum elemento dentro do intervalo especificado.
type: docs
weight: 92
url: /pt/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função

Verifica se um span somente leitura contém algum elemento dentro do intervalo especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span (deve ser comparável) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser pesquisado |
| lowInclusive | const T\& | O limite inferior (inclusivo) |
| highInclusive | const T\& | O limite superior (inclusivo) |

### Valor de retorno

true se algum elemento dentro do intervalo for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) função

Verifica se um span mutável contém algum elemento dentro do intervalo especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span (deve ser comparável) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável a ser pesquisado |
| lowInclusive | const T\& | O limite inferior (inclusivo) |
| highInclusive | const T\& | O limite superior (inclusivo) |

### Valor de retorno

true se algum elemento dentro do intervalo for encontrado, false caso contrário

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)