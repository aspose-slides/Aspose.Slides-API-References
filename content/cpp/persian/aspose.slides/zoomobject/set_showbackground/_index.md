---
title: set_ShowBackground()
second_title: Aspose.Slides برای مرجع API C++
description: "مقداری را تنظیم می‌کند که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا نه. نوع bool. مقدار پیش‌فرض: true"
type: docs
weight: 66
url: /fa/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) متد

مقداری را تعیین می‌کند که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا نه. نوع **bool**. مقدار پیش‌فرض: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## ملاحظات

مثال نمایش می‌دهد که چگونه پس‌زمینه تصویر یک شی Zoom حذف می‌شود:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## مراجع دیگر

* کلاس [ZoomObject](../)
* فضای‌نامی [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)