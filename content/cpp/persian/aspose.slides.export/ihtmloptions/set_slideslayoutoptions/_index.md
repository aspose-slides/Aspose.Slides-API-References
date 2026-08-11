---
title: set_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه ISlidesLayoutOptions را تنظیم می‌کند.
type: docs
weight: 222
url: /fa/aspose.slides.export/ihtmloptions/set_slideslayoutoptions/
---
## IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) متد

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/) را تنظیم می‌کند.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [IHtmlOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)