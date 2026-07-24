---
title: set_TransitionDuration()
second_title: Aspose.Slides C++ API Referansı
description: "Zoom ve slayt arasındaki geçiş süresini ayarlar. float yazın. Varsayılan değer: 1.0f"
type: docs
weight: 118
url: /tr/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) metot


Yakınlaştırma ve slayt arasındaki geçiş süresini ayarlar. **float** yazın. Varsayılan değer: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Açıklamalar


Belirtilmezse (TransitionDur = 0), hedef slayt geçişi ve bu geçişle ilişkili zamanlamaları kullanır. 

örnek, Zoom ve slayt arasındaki geçiş süresinin değiştirilmesini gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## İlgili

* Sınıf [IZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)