---
title: ToUInt32()
second_title: Referência da API Aspose.Slides para C++
description: Converte quatro bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 32 bits.
type: docs
weight: 105
url: /pt/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

Converte quatro bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 32 bits.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 32 bits resultante da conversão

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

Converte quatro bytes do array especificado a partir do índice especificado para um valor inteiro sem sinal de 32 bits.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 32 bits resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)