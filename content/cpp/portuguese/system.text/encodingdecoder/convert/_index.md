---
title: Convert()
second_title: Referência da API Aspose.Slides for C++
description: Converte bytes em caracteres.
type: docs
weight: 1
url: /pt/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) método

Converte bytes em caracteres.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamanho da matriz de destino. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do decodificador após o cálculo. |
| bytesUsed | int\& | Referência a variável para armazenar a contagem de bytes lidos. |
| charsUsed | int\& | Referência a variável para armazenar a contagem de caracteres escritos. |
| completed | **bool**\& | Referência a variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) método

Converte bytes em caracteres.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| byteIndex | int | Deslocamento do buffer de entrada. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Deslocamento da matriz de destino. |
| charCount | int | Tamanho da matriz de destino. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do decodificador após o cálculo. |
| bytesUsed | int\& | Referência a variável para armazenar a contagem de bytes lidos. |
| charsUsed | int\& | Referência a variável para armazenar a contagem de caracteres escritos. |
| completed | **bool**\& | Referência a variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)