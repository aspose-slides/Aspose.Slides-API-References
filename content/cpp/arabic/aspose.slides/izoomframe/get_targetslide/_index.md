---
title: get_TargetSlide()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على كائن الشريحة الذي يرتبط به كائن Slide Zoom. اقرأ ISlide.
type: docs
weight: 1
url: /ar/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() طريقة

يحصل على كائن الشريحة الذي يرتبط به كائن Zoom [Slide](../../slide/). اقرأ [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## ملاحظات

المثال التالي يوضح تغيير الشريحة المستهدفة وإنشاء صورة جديدة لكائن Zoom [Slide](../../slide/):

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [ISlide](../../islide/)
* الفئة [IZoomFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)