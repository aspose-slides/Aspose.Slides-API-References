---
title: set_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن ارائه ISlidesLayoutOptions را تنظیم می‌کند.
type: docs
weight: 183
url: /fa/aspose.slides.export/tiffoptions/set_slideslayoutoptions/
---
## TiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) متد

حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [TiffOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)