---
title: set_ReturnToParent()
second_title: Aspose.Slides C++ için API Referansı
description: "Slayt gösterisinde gezinme davranışını ayarlar. bool yazın. Varsayılan değer: false"
type: docs
weight: 40
url: /tr/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metot


Slayt gösterisinde gezinme davranışını ayarlar. **bool** yazın. Varsayılan değer: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Açıklamalar


Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir. 

Örnek: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Diğerlerine Bakın

* Sınıf [ZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)