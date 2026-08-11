---
title: set_SkipJavaScriptLinks()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. نوشتن bool. مقدار پیش‌فرض false است.
type: docs
weight: 118
url: /fa/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) متد


مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript رد شوند یا نه. نوشتن **bool**. مقدار پیش‌فرض **false** است.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## توضیحات


زمانی که این ویژگی به **true** تنظیم شود، پیوندهای ابرمتنی با فراخوانی‌های JavaScript در هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی به **false** تنظیم شود، تمام پیوندهای ابرمتنی ذخیره می‌شوند.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## موارد مرتبط

* کلاس [SaveOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)