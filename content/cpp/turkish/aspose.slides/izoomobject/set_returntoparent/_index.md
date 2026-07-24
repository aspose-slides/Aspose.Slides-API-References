---
title: set_ReturnToParent()
second_title: Aspose.Slides için C++ API Referansı
description: "Slayt gösterisinde gezinme davranışını ayarlar. bool yazın. Varsayılan değer: false"
type: docs
weight: 40
url: /tr/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metod

Slayt gösterisinde gezinme davranışını ayarlar. **bool** yazın. Varsayılan değer: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Açıklamalar

Özelliğin doğru değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir.

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ayrıca Bakınız

* Sınıf [IZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)