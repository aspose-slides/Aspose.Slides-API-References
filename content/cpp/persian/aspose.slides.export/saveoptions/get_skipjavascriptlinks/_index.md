---
title: get_SkipJavaScriptLinks()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا هنگام ذخیره ارائه، لینک‌های هیپرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. خواندنی bool. مقدار پیش‌فرض false است.
type: docs
weight: 105
url: /fa/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() متد

مشخص می‌کند که آیا هنگام ذخیره ارائه لینک‌های هیپرمتنی با فراخوانی‌های جاوااسکریپت نادیده گرفته شوند یا خیر. خواندنی **bool**. مقدار پیش‌فرض **false** است.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## توضیحات

هنگامی که این ویژگی به **true** تنظیم شود، لینک‌های هیپرمتنی با فراخوانی‌های جاوااسکریپت هنگام ذخیره نادیده گرفته می‌شوند.

هنگامی که این ویژگی به **false** تنظیم شود، تمام لینک‌های هیپرمتنی ذخیره می‌شوند.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## موارد مرتبط

* کلاس [SaveOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)