---
title: set_ShowBackground()
second_title: مرجع API Aspose.Slides برای C++
description: "مقداری را تنظیم می‌کند که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا نه. نوع bool. مقدار پیش‌فرض: true"
type: docs
weight: 66
url: /fa/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) متد

مقدار را تنظیم می‌کند که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا نه. نوع **bool**. مقدار پیش‌فرض: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## ملاحظات

مثال حذف پس‌زمینه تصویر یک شی Zoom را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## موارد مرتبط

* کلاس [IZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)