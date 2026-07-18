---
title: GetEncoding()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει κωδικοποίηση με βάση το όνομα.
type: docs
weight: 508
url: /el/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) μέθοδος

Λαμβάνει την κωδικοποίηση με βάση το όνομα.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### Τιμή επιστροφής

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) μέθοδος

Λαμβάνει την κωδικοποίηση με βάση τον κώδικα σελίδας.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |

### Τιμή επιστροφής

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) μέθοδος

Λαμβάνει την κωδικοποίηση με βάση τον κώδικα σελίδας.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Τιμή επιστροφής

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) μέθοδος

Λαμβάνει την κωδικοποίηση με βάση το όνομα.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Τιμή επιστροφής

[Encoding](../) of specified name.

## Δείτε επίσης

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Encoding](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)