---
title: get_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام صدور یک ارائه را دریافت می‌کند ISlidesLayoutOptions.
type: docs
weight: 1
url: /fa/aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() متد

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [PdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)