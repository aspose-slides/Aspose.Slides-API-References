---
title: set_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را تنظیم می‌کند ISlidesLayoutOptions.
type: docs
weight: 14
url: /fa/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) متد


حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [HtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)