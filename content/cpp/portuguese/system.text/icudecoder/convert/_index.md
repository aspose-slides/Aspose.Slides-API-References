---
title: Convert()
second_title: Referência da API Aspose.Slides para C++
description: Converte bytes em caracteres.
type: docs
weight: 66
url: /pt/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) método

Converte bytes em caracteres.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| byteIndex | int | Deslocamento do buffer de entrada. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Deslocamento do array de destino. |
| charCount | int | Tamanho do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do decodificador após o cálculo. |
| bytesUsed | int\& | Referência a variável que armazena a contagem de bytes lidos. |
| charsUsed | int\& | Referência a variável que armazena a contagem de caracteres escritos. |
| completed | **bool**\& | Referência a variável que será definida como true se o buffer de entrada estiver esgotado e como false caso contrário. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) método

Converte bytes em caracteres.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| byteCount | int | Tamanho do buffer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamanho do array de destino. |
| flush | **bool** | Se true, limpa o estado interno do decodificador após o cálculo. |
| bytesUsed | int\& | Referência a variável que armazena a contagem de bytes lidos. |
| charsUsed | int\& | Referência a variável que armazena a contagem de caracteres escritos. |
| completed | **bool**\& | Referência a variável que será definida como true se o buffer de entrada estiver esgotado e como false caso contrário. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUDecoder](../)
* Espaço de nomes [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)