---
title: ToDouble()
second_title: Referência da API Aspose.Slides para C++
description: Converte oito bytes do array especificado a partir do índice especificado para valor de ponto flutuante de precisão dupla.
type: docs
weight: 144
url: /pt/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para valor de ponto flutuante de precisão dupla.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém os bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor de ponto flutuante de precisão dupla resultante da conversão

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) método


Converte oito bytes do array especificado a partir do índice especificado para valor de ponto flutuante de precisão dupla.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém os bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor de ponto flutuante de precisão dupla resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)