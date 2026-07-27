---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.
type: docs
weight: 209
url: /pt/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array que contém os bytes a gravar. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de elementos no subintervalo a ser gravado. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array que contém os bytes a gravar |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser gravado começa |
| size | **int32_t** | O número de elementos no subintervalo a ser gravado |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)