---
title: get_ShowBackground()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقداری را دریافت می‌کند که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا نه. خواندن bool. مقدار پیش‌فرض: true"
type: docs
weight: 53
url: /fa/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() متد

مقداری را دریافت می‌کند که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا نه. خواندن **bool**. مقدار پیش‌فرض: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## توضیحات

مثال حذف پس‌زمینه تصویر یک شیء Zoom را نشان می‌دهد:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## مراجع

* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)