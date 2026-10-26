---
title: ToInt64()
second_title: Referência de API do Aspose.Slides para C++
description: Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro de 64 bits.
type: docs
weight: 79
url: /pt/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro de 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array onde começar a pegar bytes para conversão |

### Valor de Retorno

valor inteiro de 64 bits resultante da conversão

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro de 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array onde começar a pegar bytes para conversão |

### Valor de Retorno

valor inteiro de 64 bits resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)