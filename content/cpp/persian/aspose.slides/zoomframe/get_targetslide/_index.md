---
title: get_TargetSlide()
second_title: مرجع API Aspose.Slides برای C++
description: شی اسلایدی که شی Slide Zoom به آن پیوند می‌دهد را دریافت می‌کند. مطالعه کنید ISlide.
type: docs
weight: 1
url: /fa/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() متد

شی اسلایدی که شی Zoom [Slide](../../slide/) به آن پیوند می‌دهد را دریافت می‌کند. مطالعه کنید [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## توضیحات

مثال بعدی نشان می‌دهد که چگونه اسلاید هدف تغییر می‌کند و تصویر جدیدی برای شی Zoom [Slide](../../slide/) ایجاد می‌کند:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [ZoomFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)