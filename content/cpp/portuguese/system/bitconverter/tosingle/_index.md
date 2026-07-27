---
title: ToSingle()
second_title: Referência da API Aspose.Slides para C++
description: Converte quatro bytes do array especificado, começando no índice especificado, para um valor de ponto flutuante de precisão simples.
type: docs
weight: 131
url: /pt/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) método


Converte quatro bytes do array especificado, começando no índice especificado, para um valor de ponto flutuante de precisão simples.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura dos bytes para conversão |

### Valor de Retorno

Valor de ponto flutuante de precisão simples resultante da conversão

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) método


Converte quatro bytes do array especificado, começando no índice especificado, para um valor de ponto flutuante de precisão simples.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura dos bytes para conversão |

### Valor de Retorno

Valor de ponto flutuante de precisão simples resultante da conversão

## Ver Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)