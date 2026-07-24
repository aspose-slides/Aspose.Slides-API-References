---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom ve slide arasındaki geçiş süresini ayarlar. float yazın. Varsayılan değer: 1.0f"
type: docs
weight: 118
url: /tr/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metot

Zoom ve slayt arasındaki geçiş süresini ayarlar. **float** yazın. Varsayılan değer: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Açıklamalar

Belirtilmezse (TransitionDur = 0), hedef slayt geçişini ve o geçişle ilişkili zamanlamaları kullanır.

örnek, Zoom ve slayt arasındaki geçiş süresini değiştirmeyi gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## İlgili

* Sınıf [ZoomObject](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)