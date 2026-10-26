---
title: set_TargetSlide()
second_title: Aspose.Slides لمرجع API C++
description: يضبط كائن الشريحة الذي يرتبط به كائن Slide Zoom. اكتب ISlide.
type: docs
weight: 14
url: /ar/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) طريقة

يضبط كائن الشريحة الذي يرتبط به كائن [Slide](../../slide/) Zoom. اكتب [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## ملاحظات

يوضح المثال التالي تغيير شريحة الهدف وإنشاء صورة جديدة لكائن [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [ZoomFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)