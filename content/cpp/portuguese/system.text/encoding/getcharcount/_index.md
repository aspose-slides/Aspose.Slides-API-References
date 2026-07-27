---
title: GetCharCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de caracteres necessários para decodificar um buffer de bytes.
type: docs
weight: 261
url: /pt/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) método

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

### Valor de retorno

Número de caracteres.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) método

Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes a decodificar. |

### Valor de retorno

Número de caracteres.

## Encoding::GetCharCount(const uint8_t *, int) método

Obtém o número de caracteres necessários para decodificar um buffer de bytes.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes a decodificar. |
| count | int | Contagem de bytes. |

### Valor de retorno

Número de caracteres.

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)