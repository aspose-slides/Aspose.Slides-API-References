---
title: get_SkipJavaScriptLinks()
second_title: مرجع برنامه‌نویسی Aspose.Slides برای C++
description: مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای حاوی فراخوانی‌های JavaScript را نادیده بگیرد. قابل‌خواندن **bool**. مقدار پیش‌فرض **false** است.
type: docs
weight: 105
url: /fa/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() متد

مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای دارای فراخوانی JavaScript را نادیده بگیرد. قابل‌خواندن **bool**. مقدار پیش‌فرض **false** است.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## توضیحات

هنگامی که این ویژگی به **true** تنظیم شود، پیوندهای دارای فراخوانی JavaScript هنگام ذخیره نادیده گرفته می‌شوند.

هنگامی که این ویژگی به **false** تنظیم شود، تمام پیوندها ذخیره می‌شوند.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## موارد مرتبط

* کلاس [ISaveOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)