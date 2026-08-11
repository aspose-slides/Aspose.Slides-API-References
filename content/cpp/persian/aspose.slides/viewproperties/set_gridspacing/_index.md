---
title: set_GridSpacing()
second_title: Aspose.Slides برای مرجع API C++
description: فاصلهٔ شبکه‌ای را تنظیم می‌کند که باید برای شبکهٔ پایهٔ سند ارائه استفاده شود، بر حسب نقطه. مقدار float را بنویسید.
type: docs
weight: 105
url: /fa/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) متد

فاصلهٔ شبکه‌ای را تنظیم می‌کند که باید برای شبکهٔ پایهٔ سند ارائه استفاده شود، بر حسب نقطه. مقدار **float** را بنویسید.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## توضیحات

مقدار فاصلهٔ شبکه باید یک عدد مثبت باشد. بازهٔ معمولی مقدار از 1 میلی‌متر (2.8349607 نقطه) تا 2 اینچ (144 نقطه) است.

کد نمونهٔ زیر نشان می‌دهد چگونه فاصلهٔ شبکه را در یک ارائهٔ PowerPoint تغییر داد.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [ViewProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)