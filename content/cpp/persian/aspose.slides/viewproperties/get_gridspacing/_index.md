---
title: get_GridSpacing()
second_title: مرجع API Aspose.Slides برای C++
description: فاصلهٔ شبکه را که باید برای شبکهٔ زیر سند ارائه استفاده شود، بر حسب نقطه برمی‌گرداند. خواندنی float.
type: docs
weight: 92
url: /fa/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() متد

فاصلهٔ شبکه‌ای را که باید برای شبکهٔ زیر سند ارائه استفاده شود، به نقطه برمی‌گرداند. خواندنی **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## ملاحظات

مقدار فاصلهٔ شبکه باید عددی مثبت باشد. بازهٔ مقدار معمولی از ۱ میلی‌متر (۲.۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

کد نمونهٔ زیر نشان می‌دهد چگونه فاصلهٔ شبکه را در یک ارائهٔ PowerPoint تغییر دهیم.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## مراجع دیگر

* کلاس [ViewProperties](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)