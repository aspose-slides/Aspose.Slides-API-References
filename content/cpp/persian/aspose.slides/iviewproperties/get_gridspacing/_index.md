---
title: get_GridSpacing()
second_title: Aspose.Slides برای C++ مرجع API
description: فاصله‌ شبکه‌ای را که باید برای شبکه زیرساخت سند ارائه استفاده شود، به نقطه برمی‌گرداند. خواندنی float.
type: docs
weight: 92
url: /fa/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() متد


فاصله‌ شبکه‌ای را که باید برای شبکه زیرساخت سند ارائه استفاده شود، به نقطه برمی‌گرداند. خواندنی **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## توضیحات


مقدار فاصله‌ شبکه باید یک عدد مثبت باشد. بازهٔ مقدار معمولی از ۱ میلی‌متر (۲.۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

کد نمونهٔ زیر نشان می‌دهد چگونه می‌توان فاصله‌ شبکه را در یک ارائهٔ PowerPoint تغییر داد. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IViewProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)