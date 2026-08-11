---
title: set_TargetSlide()
second_title: مرجع API Aspose.Slides للـ C++
description: يعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. اكتب ISlide.
type: docs
weight: 14
url: /ar/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) طريقة


يعيّن كائن الشريحة الذي يرتبط به كائن Zoom [Slide](../../slide/). اكتب [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## ملاحظات


المثال التالي يوضح تغيير الشريحة المستهدفة وإنشاء صورة جديدة لكائن Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [IZoomFrame](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)