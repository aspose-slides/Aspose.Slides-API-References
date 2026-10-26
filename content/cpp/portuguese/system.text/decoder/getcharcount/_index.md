---
title: GetCharCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de caracteres necessários para decodificar um buffer.
type: docs
weight: 40
url: /pt/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Obtém o número de caracteres necessários para decodificar um buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes para decodificar. |
| index | int | [Buffer](../../../system/buffer/) deslocamento. |
| count | int | Número de bytes a decodificar. |

### Valor de Retorno

Número de caracteres necessários para decodificar o buffer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

Obtém o número de caracteres necessários para decodificar um buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes para decodificar. |
| index | int | [Buffer](../../../system/buffer/) deslocamento. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do decodificador após o cálculo. |

### Valor de Retorno

Número de caracteres necessários para decodificar o buffer.

## Decoder::GetCharCount(const uint8_t *, int, bool) method

Obtém o número de caracteres necessários para decodificar um buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes para decodificar. |
| count | int | Número de bytes a decodificar. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do decodificador após o cálculo. |

### Valor de Retorno

Número de caracteres necessários para decodificar o buffer.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)