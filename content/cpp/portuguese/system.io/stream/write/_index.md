---
title: Write()
second_title: Aspose.Slides para C++ Referência da API
description: Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.
type: docs
weight: 53
url: /pt/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a ser gravados |
| offset | **int32_t** | Um índice baseado em 0 do elemento em **buffer** onde o subintervalo a ser gravado começa |
| count | **int32_t** | O número de elementos no subintervalo a ser gravado |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização de array contendo os bytes a ser gravados |
| offset | **int32_t** | Um índice baseado em 0 do elemento em **buffer** onde o subintervalo a ser gravado começa |
| count | **int32_t** | O número de elementos no subintervalo a ser gravado |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| N | O tamanho do array de pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | O array de pilha contendo os bytes a ser gravados |
| offset | **int32_t** | Um índice baseado em 0 do elemento em **buffer** onde o subintervalo a ser gravado começa |
| count | **int32_t** | O número de elementos no subintervalo a ser gravado |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Grava o subintervalo especificado de bytes da faixa de bytes especificada no fluxo.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | A faixa de bytes da qual ler os bytes gravados |

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Stream](../)
* Classe [ReadOnlySpan](../../../system/readonlyspan/)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)