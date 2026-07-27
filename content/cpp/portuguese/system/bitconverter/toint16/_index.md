---
title: ToInt16()
second_title: Referência da API Aspose.Slides para C++
description: Converte dois bytes do array especificado a partir do índice especificado para um valor inteiro de 16 bits.
type: docs
weight: 53
url: /pt/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) método


Converte dois bytes do array especificado a partir do índice especificado para um valor inteiro de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém os bytes a converter |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

16-bit integer value resulting from conversion

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) método


Converte dois bytes do array especificado a partir do índice especificado para um valor inteiro de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém os bytes a converter |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

16-bit integer value resulting from conversion

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)