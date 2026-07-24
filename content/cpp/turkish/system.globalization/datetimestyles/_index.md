---
title: DateTimeStyles
second_title: Aspose.Slides for C++ API Referansı
description: Tarih ve saat biçimlendirme seçeneklerini tanımlar. Bit bayrakları.
type: docs
weight: 456
url: /tr/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Tarih ve saat biçimlendirme seçeneklerini tanımlar. Bit bayrakları.

```cpp
enum class DateTimeStyles : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Varsayılan. |
| AllowLeadingWhite | 1 | Başlangıçtaki boşlukları yoksay. |
| AllowTrailingWhite | 2 | Sonundaki boşlukları yoksay. |
| AllowInnerWhite | 4 | İçteki boşlukları yoksay. |
| AllowWhiteSpaces | n/a | Tüm boşlukları yoksay. |
| NoCurrentDateDefault | 8 | Bir tarih/saat dizesi ayrıştırılırken, yıl/ay/gün tümü eksikse, varsayılan tarihi geçerli yıl/ay/gün yerine 0001/1/1 olarak ayarla. |
| AdjustToUniversal | 16 | Bir tarih/saat dizesi ayrıştırılırken, bir saat dilimi belirticisi ("GMT","Z","+xxxx","-xxxx") mevcutsa, ayrıştırılan zamanı GMT'ye göre ayarlarız. |
| AssumeLocal | 32 | Saat dilimi belirtilmemişse, yerel saat dilimini kullan. |
| AssumeUniversal | 64 | Saat dilimi belirtilmemişse, UTC'yi kullan. |
| RoundtripKind | 128 | Girişin belirsiz, yerel veya UTC olup olmadığını korumaya çalış. |

## Ayrıca Bakınız

* Ad Alanı [System::Globalization](../)
* Kütüphane [Aspose.Slides](../../)