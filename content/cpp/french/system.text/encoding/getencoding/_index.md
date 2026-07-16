---
title: GetEncoding()
second_title: Référence API Aspose.Slides pour C++
description: Obtient l'encodage par nom.
type: docs
weight: 508
url: /fr/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) méthode


Obtient l’encodage par nom.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nom. |

### Valeur de retour

[Encoding](../) du nom spécifié.

## Encoding::GetEncoding(int) méthode


Obtient l’encodage par codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Numéro de codepage. |

### Valeur de retour

[Encoding](../) du codepage spécifié.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) méthode


Obtient l’encodage par codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Numéro de codepage. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback à utiliser pour l’encodage. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback à utiliser pour le décodage. |

### Valeur de retour

[Encoding](../) du codepage spécifié.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) méthode


Obtient l’encodage par nom.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nom. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback à utiliser pour l’encodage. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback à utiliser pour le décodage. |

### Valeur de retour

[Encoding](../) du nom spécifié.

## Voir aussi

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)