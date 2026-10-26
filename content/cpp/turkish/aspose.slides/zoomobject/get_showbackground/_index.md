---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom nesnesinin hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır. Okur bool. Varsayılan değer: true"
type: docs
weight: 53
url: /tr/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() metodu

Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır. Okur **bool**. Varsayılan değer: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
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

* Sınıf [ZoomObject](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)