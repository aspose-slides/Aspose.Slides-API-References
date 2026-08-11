---
title: get_TargetSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: شیء اسلایدی را که شیء Slide Zoom به آن پیوند می‌دهد، دریافت می‌کند. ISlide را بخوانید.
type: docs
weight: 1
url: /fa/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() متد

شیء اسلایدی که شیء Zoom [Slide](../../slide/) به آن پیوند می‌زند را دریافت می‌کند. [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## ملاحظات

مثال بعدی نشان می‌دهد که چگونه اسلاید هدف را تغییر داده و تصویر جدیدی برای شیء Zoom [Slide](../../slide/) ایجاد می‌کند:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [IZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)