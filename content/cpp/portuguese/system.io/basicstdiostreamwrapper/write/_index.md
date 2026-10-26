---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Se o modo de encapsulamento for binário, grava no fluxo o subintervalo especificado de bytes do array de bytes especificado; caso contrário, converte o subintervalo especificado de bytes do array de bytes especificado para o tipo char_type e então grava o resultado no fluxo.
type: docs
weight: 79
url: /pt/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Se o modo de encapsulamento for binário, grava no fluxo o sub-intervalo especificado de bytes do array de bytes especificado; caso contrário, converte o sub-intervalo especificado de bytes do array de bytes especificado para o tipo char_type e então grava o resultado no fluxo.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem gravados |
| offset | **int32_t** | Um índice base 0 do elemento em **buffer** onde começa o sub-intervalo a ser gravado |
| count | **int32_t** | O número de elementos no sub-intervalo a ser gravado |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Grava o sub-intervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array contendo os bytes a serem gravados |
| offset | **int32_t** | Um índice base 0 do elemento em **buffer** onde começa o sub-intervalo a ser gravado |
| count | **int32_t** | O número de elementos no sub-intervalo a ser gravado |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)