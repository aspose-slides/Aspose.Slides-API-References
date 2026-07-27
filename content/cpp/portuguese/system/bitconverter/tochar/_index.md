---
title: ToChar()
second_title: Referência da API Aspose.Slides para C++
description: Converte dois bytes do array especificado, começando no índice especificado, para o valor char_t.
type: docs
weight: 40
url: /pt/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method


Converte dois bytes do array especificado, começando no índice especificado, para o valor char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array em que começar a pegar bytes para conversão |

### Valor de Retorno

char_t valor resultante da conversão

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converte dois bytes do array especificado, começando no índice especificado, para o valor char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView que contém bytes a serem convertidos |
| startIndex | int | [Index](../../index/) no array em que começar a pegar bytes para conversão |

### Valor de Retorno

char_t valor resultante da conversão

## Ver Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)