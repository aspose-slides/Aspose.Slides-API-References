---
title: get_ShowBackground()
second_title: مرجع API Aspose.Slides برای C++
description: "مقداری را برمی‌گرداند که مشخص می‌کند آیا Zoom پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه. خواندنی bool. مقدار پیش‌فرض: true"
type: docs
weight: 53
url: /fa/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() متد


مقداری را برمی‌گرداند که مشخص می‌کند آیا Zoom پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه. خواندنی **bool**. مقدار پیش‌فرض: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## توضیحات


مثال نشان می‌دهد که چگونه پس‌زمینهٔ تصویر یک شیء Zoom حذف می‌شود: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## See Also

* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)