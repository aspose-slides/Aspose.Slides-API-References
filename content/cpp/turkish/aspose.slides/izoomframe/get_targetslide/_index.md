---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Slide Zoom nesnesinin bağlandığı slayt nesnesini alır. ISlide'ı okuyun.
type: docs
weight: 1
url: /tr/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() yöntemi

[Slide](../../slide/) Zoom nesnesinin bağlandığı slayt nesnesini alır. Okuyun [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Açıklamalar

Aşağıdaki örnek, hedef slaytı değiştirmeyi ve [Slide](../../slide/) Zoom nesnesi için yeni bir görüntü oluşturmayı gösterir:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)