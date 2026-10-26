---
title: GetVisualBounds()
second_title: Aspose.Slides C++ API Referansı
description: Şeklin işlenmiş içeriğinden hesaplanan görsel sınırları alır.
type: docs
weight: 677
url: /tr/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metodu


Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Dönüş Değeri

Kaydırak koordinatlarında şeklin görsel sınırlarını temsil eden bir [System::Drawing::RectangleF](../../../system.drawing/rectanglef/).

## Açıklamalar


Döndürülen dikdörtgen, şeklin render sırasında slayt koordinat alanında ürettiği tüm içeriğin eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) farklı olabilir ve işlenmiş içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, [SmartArt](../../../aspose.slides.smartart/) geometrisi ve şeklin nihai render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili öğeleri dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz. 

## Ayrıca Bakınız

* Sınıf [RectangleF](../../../system.drawing/rectanglef/)
* Sınıf [Shape](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)