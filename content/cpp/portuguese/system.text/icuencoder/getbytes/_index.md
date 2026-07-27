---
title: GetBytes()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os bytes resultantes da codificação de um buffer.
type: docs
weight: 53
url: /pt/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) método


Obtém os bytes resultantes da codificação de um buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| charIndex | int | Deslocamento do array de origem. |
| charCount | int | Comprimento do subarray de origem. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer de bytes de destino. |
| byteIndex | int | Deslocamento do buffer de destino. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do codificador após o cálculo. |

### Valor de Retorno

Número de bytes escritos.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) método


Obtém os bytes resultantes da codificação de um buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Comprimento do array de origem. |
| bytes | **uint8_t** * | Buffer de bytes de destino. |
| byteCount | int | Tamanho do buffer de destino. |
| flush | **bool** | Se verdadeiro, limpa o estado interno do codificador após o cálculo. |

### Valor de Retorno

Número de bytes escritos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoder](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)