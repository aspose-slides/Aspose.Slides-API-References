---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Se o modo de encapsulamento for binário, grava no fluxo o subintervalo especificado de bytes do array de bytes especificado; caso contrário, converte o subintervalo especificado de bytes do array de bytes especificado para o tipo char_type e então grava o resultado no fluxo. Não suportado!
type: docs
weight: 79
url: /pt/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Se o modo de encapsulamento for binário, grava no fluxo o subintervalo especificado de bytes do array de bytes especificado; caso contrário, converte o subintervalo especificado de bytes do array de bytes especificado para o tipo char_type e então grava o resultado no fluxo. Não suportado!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem gravados. |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser gravado começa. |
| count | **int32_t** | O número de elementos no subintervalo a ser gravado. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização de array contendo os bytes a serem gravados |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser gravado começa |
| count | **int32_t** | O número de elementos no subintervalo a ser gravado |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)