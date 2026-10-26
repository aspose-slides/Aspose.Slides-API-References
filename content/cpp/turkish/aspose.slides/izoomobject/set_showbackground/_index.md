---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri ayarlar. bool yazın. Varsayılan değer: true"
type: docs
weight: 66
url: /tr/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metodu

Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri ayarlar. **bool** yazın. Varsayılan değer: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Açıklamalar

Örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Diğer Bağlantılar

* Sınıf [IZoomObject](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)