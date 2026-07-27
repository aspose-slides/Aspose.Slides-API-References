---
title: ToUInt16()
second_title: Aspose.Slides para C++ Referência da API
description: Converte dois bytes do array especificado, começando no índice especificado, para um valor inteiro sem sinal de 16 bits.
type: docs
weight: 92
url: /pt/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) método

Converte dois bytes do array especificado, começando no índice especificado, para um valor inteiro sem sinal de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 16 bits resultante da conversão

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) método

Converte dois bytes do array especificado, começando no índice especificado, para um valor inteiro sem sinal de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array no qual iniciar a captura de bytes para conversão |

### Valor de Retorno

Valor inteiro sem sinal de 16 bits resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)