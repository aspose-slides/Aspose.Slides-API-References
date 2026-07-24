---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom'ın hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri ayarlar. bool yazın. Varsayılan değer: true"
type: docs
weight: 66
url: /tr/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) yöntemi

Zoom'ın hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri ayarlar. **bool** yazın. Varsayılan değer: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Açıklamalar

örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı gösterir:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## İlgili Bağlantılar

* Sınıf [ZoomObject](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)