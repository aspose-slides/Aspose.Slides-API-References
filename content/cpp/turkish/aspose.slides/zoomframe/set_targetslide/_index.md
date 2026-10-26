---
title: set_TargetSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Slide Zoom nesnesinin bağlandığı slayt nesnesini ayarlar. ISlide yazın.
type: docs
weight: 14
url: /tr/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metod

[Slide](../../slide/) Zoom nesnesinin bağlandığı slayt nesnesini ayarlar. [ISlide](../../islide/) yazın.

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Açıklamalar

Sonraki örnek, hedef slaytı değiştirmeyi gösterir ve [Slide](../../slide/) Zoom nesnesi için yeni bir görüntü oluşturur:

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## İlgili

* Tip Tanımlaması [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [ZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)