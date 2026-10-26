---
title: get_TransitionDuration()
second_title: Aspose.Slides için C++ API Referansı
description: "Zoom ve slayt arasındaki geçişin süresini alır. float okunur. Varsayılan değer: 1.0f"
type: docs
weight: 105
url: /tr/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metot

Zoom ile slayt arasındaki geçişin süresini alır. Okunur **float**. Varsayılan değer: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Açıklamalar

Belirtilmezse (TransitionDur = 0), hedef slayt geçişini ve bu geçişle ilişkili zamanlamaları kullanır. 

örnek, Zoom ile slayt arasındaki geçiş süresini değiştirmeyi gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Bakınız

* Sınıf [IZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)