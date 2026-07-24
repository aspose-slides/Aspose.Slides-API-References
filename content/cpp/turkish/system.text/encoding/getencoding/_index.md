---
title: GetEncoding()
second_title: Aspose.Slides for C++ API Referansı
description: Adına göre kodlamayı alır.
type: docs
weight: 508
url: /tr/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) yöntemi

Adına göre kodlamayı alır.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) adı. |

### Dönüş Değeri

[Encoding](../) belirtilen adın.

## Encoding::GetEncoding(int) yöntemi

Kod sayfasına göre kodlamayı alır.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codepage | int | Kod sayfası numarası. |

### Dönüş Değeri

[Encoding](../) belirtilen kod sayfasının.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) yöntemi

Kod sayfasına göre kodlamayı alır.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codepage | int | Kod sayfası numarası. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Kodlama için kullanılacak geri dönüş. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Kod çözme için kullanılacak geri dönüş. |

### Dönüş Değeri

[Encoding](../) belirtilen kod sayfasının.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) yöntemi

Adına göre kodlamayı alır.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) adı. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Kodlama için kullanılacak geri dönüş. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Kod çözme için kullanılacak geri dönüş. |

### Dönüş Değeri

[Encoding](../) belirtilen adın.

## Ayrıca Bakınız

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Encoding](../)
* Ad Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)