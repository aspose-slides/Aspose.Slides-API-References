---
title: GetEncoding()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene la codifica per nome.
type: docs
weight: 508
url: /it/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metodo


Ottiene la codifica per nome.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nome. |

### Valore di ritorno

[Encoding](../) del nome specificato.

## Encoding::GetEncoding(int) metodo


Ottiene la codifica per codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codepage | int | Numero della codepage. |

### Valore di ritorno

[Encoding](../) della codepage specificata.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metodo


Ottiene la codifica per codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codepage | int | Numero della codepage. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback da utilizzare per la codifica. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback da utilizzare per la decodifica. |

### Valore di ritorno

[Encoding](../) della codepage specificata.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metodo


Ottiene la codifica per nome.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nome. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback da utilizzare per la codifica. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback da utilizzare per la decodifica. |

### Valore di ritorno

[Encoding](../) del nome specificato.

## Vedi anche

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Classe [String](../../../system/string/)
* Classe [Encoding](../)
* Namespace [System::Text](../../)
* Libreria [Aspose.Slides](../../../)