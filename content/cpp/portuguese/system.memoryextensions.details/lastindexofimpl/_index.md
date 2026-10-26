---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ Referência da API
description: Encontra o último índice de um valor em um span.
type: docs
weight: 14
url: /pt/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function

Encontra o último índice de um valor em um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) para busca |
| length | **int32_t** | Comprimento para buscar dentro |
| value | const T\& | Valor a encontrar |

### Valor de retorno

Último índice do valor, ou -1 se não encontrado

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)