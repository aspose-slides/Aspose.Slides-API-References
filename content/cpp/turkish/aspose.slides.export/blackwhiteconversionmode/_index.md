---
title: BlackWhiteConversionMode
second_title: Aspose.Slides for C++ API Referansı
description: Kaydırma görüntülerinin iki tonlu görüntülere nasıl dönüştürüleceğini kontrol eden seçenekler sağlar.
type: docs
weight: 820
url: /tr/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Kaydırma görüntülerinin iki tonlu görüntülere nasıl dönüştürüleceğini kontrol eden seçenekler sağlar.

```cpp
enum class BlackWhiteConversionMode
```

### Değerler

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Dönüştürme algoritması olmadığını belirtir. TIFF codec'inde uygulanmış algoritma kullanılacaktır. (Default) |
| Dithering | 1 | Dithering algoritmasını (Floyd-Steinberg) belirtir. |
| DitheringFloydSteinberg | 2 | Floyd-Steinberg dithering algoritmasını belirtir. |
| Auto | 3 | Otomatik olarak hesaplanan eşik algoritmasını (Otsu) belirtir. |
| AutoOtsu | 4 | Otomatik olarak hesaplanan Otsu eşik algoritmasını belirtir. |
| Threshold25 | 5 | Statik eşik algoritmasını (25%) belirtir. |
| Threshold50 | 6 | Statik eşik algoritmasını (50%) belirtir. |
| Threshold75 | 7 | Statik eşik algoritmasını (75%) belirtir. |

## Diğer

* İsim Uzayı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)