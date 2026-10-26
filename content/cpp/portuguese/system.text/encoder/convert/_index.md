---
title: Convert()
second_title: Referência da API Aspose.Slides para C++
description: Converte caracteres em bytes.
type: docs
weight: 79
url: /pt/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Converte caracteres em bytes.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| charIndex | int | Deslocamento do buffer de entrada. |
| charCount | int | Tamanho do buffer de entrada. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de bytes de destino. |
| byteIndex | int | Deslocamento do array de destino. |
| byteCount | int | Tamanho do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do codificador após o cálculo. |
| charsUsed | int\& | Referência à variável que armazena a contagem de caracteres lidos. |
| bytesUsed | int\& | Referência à variável que armazena a contagem de bytes gravados. |
| completed | **bool**\& | Referência à variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Converte caracteres em bytes.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Tamanho do buffer de entrada. |
| bytes | **uint8_t** * | Buffer de bytes de destino. |
| byteCount | int | Tamanho do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do codificador após o cálculo. |
| charsUsed | int\& | Referência à variável que armazena a contagem de caracteres lidos. |
| bytesUsed | int\& | Referência à variável que armazena a contagem de bytes gravados. |
| completed | **bool**\& | Referência à variável que será definida como true se o buffer de entrada for esgotado e como false caso contrário. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)