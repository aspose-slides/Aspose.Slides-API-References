---
title: get_ReturnToParent()
second_title: Aspose.Slides için C++ API Referansı
description: "Slayt gösterisindeki gezinme davranışını alır. bool okur. Varsayılan değer: false"
type: docs
weight: 27
url: /tr/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metodu

Slayt gösterisindeki gezinme davranışını alır. **bool** okur. Varsayılan değer: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Açıklamalar

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir.

Örnek:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ayrıca Bakınız

* Sınıf [ZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)