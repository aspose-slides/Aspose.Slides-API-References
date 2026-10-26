---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır. bool okur. Varsayılan değer: true"
type: docs
weight: 53
url: /tr/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() method


Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır. **bool** okur. Varsayılan değer: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Açıklamalar


Örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı göstermektedir:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Ayrıca bakınız

* Sınıf [IZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)