---
title: GetChars()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os caracteres que resultam da decodificação de um buffer.
type: docs
weight: 53
url: /pt/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) método


Obtém os caracteres resultantes da decodificação de um buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a serem decodificados. |
| byteIndex | int | Deslocamento do buffer de entrada. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Deslocamento do array de destino. |

### Valor de Retorno

Número de caracteres gravados.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) método


Obtém os caracteres resultantes da decodificação de um buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a serem decodificados. |
| byteIndex | int | Deslocamento do buffer de entrada. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Deslocamento do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do decodificador após o cálculo. |

### Valor de Retorno

Número de caracteres gravados.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) método


Obtém os caracteres resultantes da decodificação de um buffer.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a serem decodificados. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamanho do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do decodificador após o cálculo. |

### Valor de Retorno

Número de caracteres gravados.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)