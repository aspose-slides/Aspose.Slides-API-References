---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Slide Zoom nesnesinin bağlandığı slayt nesnesini alır. Read ISlide.
type: docs
weight: 1
url: /tr/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() yöntemi


Hedef slayta bağlanan [Slide](../../slide/) Zoom nesnesinin slayt nesnesini alır. Oku [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Açıklamalar


Sonraki örnek, hedef slaytı değiştirmeyi gösterir ve [Slide](../../slide/) Zoom nesnesi için yeni bir görüntü oluşturur: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [ZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)