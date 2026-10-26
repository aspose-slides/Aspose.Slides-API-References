---
title: get_TargetSlide()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على كائن الشريحة الذي يرتبط به كائن Slide Zoom. اقرأ ISlide.
type: docs
weight: 1
url: /ar/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() طريقة

يحصل على كائن الشريحة الذي يربطه كائن [Slide](../../slide/) Zoom. اقرأ [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## ملاحظات

المثال التالي يوضح تغيير الشريحة المستهدفة وإنشاء صورة جديدة لكائن [Slide](../../slide/) Zoom: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [ZoomFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)