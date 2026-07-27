---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.
type: docs
weight: 92
url: /pt/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem escritos |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array view contendo os bytes a serem escritos |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)