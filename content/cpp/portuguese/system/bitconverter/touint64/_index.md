---
title: ToUInt64()
second_title: Referência da API Aspose.Slides para C++
description: Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 64 bits.
type: docs
weight: 118
url: /pt/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual começar a pegar bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 64 bits resultante da conversão

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual começar a pegar bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 64 bits resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)