---
title: Convert()
second_title: Referência da API Aspose.Slides para C++
description: Converte bytes em caracteres.
type: docs
weight: 79
url: /pt/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) método

Converte bytes em caracteres.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
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
| bytesUsed | int\& | Referência à variável que armazena a contagem de bytes lidos. |
| charsUsed | int\& | Referência à variável que armazena a contagem de caracteres escritos. |
| completed | **bool**\& | Referência à variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) método

Converte bytes em caracteres.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamanho da matriz de destino. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do decodificador após o cálculo. |
| bytesUsed | int\& | Referência à variável que armazena a contagem de bytes lidos. |
| charsUsed | int\& | Referência à variável que armazena a contagem de caracteres escritos. |
| completed | **bool**\& | Referência à variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)