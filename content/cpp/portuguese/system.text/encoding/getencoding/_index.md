---
title: GetEncoding()
second_title: Referência da API Aspose.Slides para C++
description: Obtém codificação por nome.
type: docs
weight: 508
url: /pt/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) método


Obtém codificação por nome.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nome. |

### Valor de Retorno

[Encoding](../) do nome especificado.

## Encoding::GetEncoding(int) método


Obtém codificação por página de código.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Número da página de código. |

### Valor de Retorno

[Encoding](../) da página de código especificada.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) método


Obtém codificação por página de código.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Número da página de código. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback a ser usado para codificação. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback a ser usado para decodificação. |

### Valor de Retorno

[Encoding](../) da página de código especificada.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) método


Obtém codificação por nome.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nome. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback a ser usado para codificação. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback a ser usado para decodificação. |

### Valor de Retorno

[Encoding](../) do nome especificado.

## Veja Também

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Classe [String](../../../system/string/)
* Classe [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)