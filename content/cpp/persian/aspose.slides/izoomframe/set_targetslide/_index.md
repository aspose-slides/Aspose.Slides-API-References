---
title: set_TargetSlide()
second_title: مرجع API Aspose.Slides برای C++
description: شیء اسلایدی را تنظیم می‌کند که شیء Slide Zoom به آن لینک می‌دهد. ISlide را بنویسید.
type: docs
weight: 14
url: /fa/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) متد

شیء اسلایدی را تنظیم می‌کند که شیء Zoom [Slide](../../slide/) به آن لینک می‌دهد. [ISlide](../../islide/) را بنویسید.

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## توضیحات

مثال بعدی تغییر اسلاید هدف را نشان می‌دهد و تصویر جدیدی برای شیء Zoom [Slide](../../slide/) ایجاد می‌کند:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [IZoomFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)