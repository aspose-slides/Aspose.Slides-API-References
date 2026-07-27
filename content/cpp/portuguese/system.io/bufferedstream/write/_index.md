---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo subjacente.
type: docs
weight: 66
url: /pt/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo subjacente.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array que contém os bytes a gravar |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a gravar começa |
| count | **int32_t** | O número de elementos no subintervalo a gravar |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo subjacente.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array que contém os bytes a gravar |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a gravar começa |
| count | **int32_t** | O número de elementos no subintervalo a gravar |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BufferedStream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)