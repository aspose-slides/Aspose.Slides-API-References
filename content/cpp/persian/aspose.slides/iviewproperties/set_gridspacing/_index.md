---
title: set_GridSpacing()
second_title: مرجع API Aspose.Slides برای C++
description: فاصلهٔ شبکه‌ای را که باید برای شبکه زیر سند ارائه استفاده شود، به واحد نقطه تنظیم می‌کند. مقدار باید به صورت float نوشته شود.
type: docs
weight: 105
url: /fa/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) متد


فاصلهٔ شبکه‌ای که باید برای شبکه زیر سند ارائه استفاده شود را تنظیم می‌کند، به واحد نقطه. **float** نوشته شود.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## توضیحات


مقدار فاصلهٔ شبکه باید عددی مثبت باشد. بازهٔ مقدار معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

کد نمونهٔ زیر نشان می‌دهد چگونه فاصلهٔ شبکه را در یک ارائهٔ PowerPoint تغییر دهیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [IViewProperties](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)