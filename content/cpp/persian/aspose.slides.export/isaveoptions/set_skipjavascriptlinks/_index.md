---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای هایپرلینک شامل فراخوانی‌های JavaScript را نادیده بگیرد یا نه. نوشتن bool. مقدار پیش‌فرض false است.
type: docs
weight: 118
url: /fa/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) متد

مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای هایپرلینک حاوی فراخوانی‌های JavaScript را نادیده بگیرد یا نه. نوشتن **bool**. مقدار پیش‌فرض **false** است.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## توضیحات

وقتی این ویژگی به **true** تنظیم شود، پیوندهای هایپرلینک حاوی فراخوانی‌های JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

وقتی این ویژگی به **false** تنظیم شود، تمام پیوندهای هایپرلینک ذخیره می‌شوند.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## همچنین ببینید

* کلاس [ISaveOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)