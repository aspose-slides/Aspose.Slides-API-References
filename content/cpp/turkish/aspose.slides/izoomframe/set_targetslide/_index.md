---
title: set_TargetSlide()
second_title: Aspose.Slides C++ API Referansı
description: Slide Zoom nesnesinin bağlandığı slayt nesnesini ayarlar. ISlide yazın.
type: docs
weight: 14
url: /tr/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metot


[Slide](../../slide/) Zoom nesnesinin bağlandığı slayt nesnesini ayarlar. Yaz [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Açıklamalar


Sonraki örnek hedef slaytı değiştirmeyi gösterir ve [Slide](../../slide/) Zoom nesnesi için yeni görüntü oluşturur: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)