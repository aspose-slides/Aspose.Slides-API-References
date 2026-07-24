---
title: get_ReturnToParent()
second_title: Aspose.Slides için C++ API Referansı
description: "Slayt gösterisinde gezinme davranışını alır. Okunur bool. Varsayılan değer: false"
type: docs
weight: 27
url: /tr/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metod

Slayt gösterisinde gezinme davranışını alır. Okunur **bool**. Varsayılan değer: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Açıklamalar

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir.

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Bakınız

* Sınıf [IZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)