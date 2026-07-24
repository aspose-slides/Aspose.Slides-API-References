---
title: CompressionLevel
second_title: Aspose.Slides for C++ API Referansı
description: OpenXML dosyası için ZIP sıkıştırma seviyelerini belirtir. Daha yüksek seviyeler, daha yavaş işleme karşılığında daha iyi sıkıştırma sağlar.
type: docs
weight: 846
url: /tr/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

OpenXML dosyası için ZIP sıkıştırma seviyelerini belirtir. Daha yüksek seviyeler, daha yavaş işleme maliyetine daha iyi sıkıştırma sağlar.

```cpp
enum class CompressionLevel
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Sıkıştırma uygulanmaz. Dosyalar olduğu gibi saklanır. |
| Level1 | 1 | En hızlı sıkıştırma, en düşük sıkıştırma oranı ile. |
| Level2 | 2 | Daha hızlı sıkıştırma, [CompressionLevel::Level1](./)'ye göre biraz daha iyi sıkıştırma oranı ile. |
| Level3 | 3 | [CompressionLevel::Level2](./)'den daha iyi sıkıştırma sağlar, orta düzeyde performans etkisiyle. |
| Level4 | 4 | [CompressionLevel::Level3](./)'den daha iyi sıkıştırma sağlar. |
| Level5 | 5 | [CompressionLevel::Level4](./)'ye göre geliştirilmiş sıkıştırma sağlar, ek işlem süresi ile. |
| Level6 | 6 | Standart sıkıştırma, sıkıştırma hızı ile dosya boyutu arasında iyi bir denge sunar. Varsayılan sıkıştırma seviyesi. |
| Level7 | 7 | [CompressionLevel::Level6](./)'den daha yüksek sıkıştırma sağlar, daha yavaş işleme ile. |
| Level8 | 8 | [CompressionLevel::Level7](./)'den daha yüksek sıkıştırma sağlar. |
| Level9 | 9 | Maksimum sıkıştırma. En küçük dosya boyutunu en yavaş işleme hızıyla üretir. |

## İlgili

* İsim Alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)