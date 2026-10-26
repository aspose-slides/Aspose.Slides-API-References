---
title: set_TargetSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: شی اسلایدی که شی Slide Zoom به آن لینک می‌شود را تنظیم می‌کند. بنویسید ISlide.
type: docs
weight: 14
url: /fa/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) متد


شی اسلایدی که شی [Slide](../../slide/) Zoom به آن لینک می‌شود را تنظیم می‌کند. بنویسید [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## توضیحات


مثال بعدی تغییر اسلاید هدف را نشان می‌دهد و تصویر جدیدی برای شی Zoom [Slide](../../slide/) ایجاد می‌کند: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [ZoomFrame](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)