---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.
type: docs
weight: 248
url: /pt/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem escritos. |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa. |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado para o fluxo.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array view contendo os bytes a serem escritos. |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa. |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [FileStream](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)