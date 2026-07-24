---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanın yolundaki her noktanın tipini belirten byte değerlerinin bir dizisini alır.
type: docs
weight: 27
url: /tr/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metodu

Gets an array of byte values that specify the type of each point in the element's path.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Açıklamalar

**0** Noktanın bir şeklin başlangıcı olduğunu gösterir.

**1** Noktanın bir çizginin iki uç noktasından biri olduğunu gösterir.

**3** Noktanın kübik Bezier eğrisinin uç noktası veya kontrol noktası olduğunu gösterir.

**7** Nokta tipini belirten üç düşük sıra biti dışındaki tüm bitleri maskeleyen.

**16** İlgili segmentin kesikli olduğunu belirtir.

**32** Noktanın bir işaretçi olduğunu belirtir.

**128** Noktanın kapalı bir alt yol (şekil) içindeki son nokta olduğunu belirtir.

**129** Hem bir çizgi segmentinin uç noktası hem de kapalı bir alt yolun son noktası olan bir veri noktasını gösterir.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ShapeElement](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)