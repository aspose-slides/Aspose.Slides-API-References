---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API Referansı
description: "Zoom ve slayt arasındaki geçişin süresini alır. float olarak okunur. Varsayılan değer: 1.0f"
type: docs
weight: 105
url: /tr/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() metodu

Zoom ve slayt arasındaki geçişin süresini alır. **float** olarak okunur. Varsayılan değer: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Açıklamalar

Eğer belirtilmezse (TransitionDur = 0), hedef slayt geçişi ve bu geçişle ilişkili zamanlamalar kullanılır. 

örnek, Zoom ve slayt arasındaki geçiş süresini değiştirmeyi gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Bakınız

* Sınıf [ZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)