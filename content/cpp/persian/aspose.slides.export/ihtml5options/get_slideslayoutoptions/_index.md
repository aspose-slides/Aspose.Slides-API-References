---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides برای C++ مرجع API
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه ISlidesLayoutOptions را دریافت می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() متد

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/) را دریافت می‌کند.

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)