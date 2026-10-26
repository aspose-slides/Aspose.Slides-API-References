---
title: SequenceEqualImpl()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se duas spans são iguais a partir de posições especificadas.
type: docs
weight: 27
url: /pt/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) função

Verifica se duas spans são iguais a partir de posições especificadas.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Primeira span |
| start | const **int32_t** | Índice inicial na primeira span |
| length | **int32_t** | Número de elementos a comparar |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Segunda span |

### Valor de retorno

true se os intervalos especificados forem iguais, false caso contrário

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espaço de nomes [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)