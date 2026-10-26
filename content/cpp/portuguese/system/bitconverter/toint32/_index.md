---
title: ToInt32()
second_title: Referência da API Aspose.Slides para C++
description: Converte quatro bytes do array especificado, começando no índice especificado, para um valor inteiro de 32 bits.
type: docs
weight: 66
url: /pt/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) método

Converte quatro bytes do array especificado, começando no índice especificado, para um valor inteiro de 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array onde começar a pegar bytes para conversão |

### Valor de Retorno

valor inteiro de 32 bits resultante da conversão

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) método

Converte quatro bytes do array especificado, começando no índice especificado, para um valor inteiro de 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array onde começar a pegar bytes para conversão |

### Valor de Retorno

valor inteiro de 32 bits resultante da conversão

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)