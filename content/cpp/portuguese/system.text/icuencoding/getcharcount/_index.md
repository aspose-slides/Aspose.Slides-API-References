---
title: GetCharCount()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o número de caracteres necessários para decodificar um buffer de bytes.
type: docs
weight: 53
url: /pt/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) método


Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Contagem de bytes. |

### Valor de Retorno

Número de caracteres.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método


Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |
| index | int | Início da fatia. |
| count | int | Tamanho da fatia. |

### Valor de Retorno

Número de caracteres.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) método


Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |

### Valor de Retorno

Número de caracteres.

## ICUEncoding::GetCharCount(const uint8_t *, int) método


Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Contagem de bytes. |

### Valor de Retorno

Número de caracteres.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)