---
title: set_Handout()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه HandoutType قرار می‌گیرند.
type: docs
weight: 14
url: /fa/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) متد

مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه قرار خواهند گرفت [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## توضیحات

مقدار پیش‌فرض **[HandoutType::Handouts6Horizontal](../../handouttype/)** است. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## موارد مرتبط

* شمارش [HandoutType](../../handouttype/)
* کلاس [HandoutLayoutingOptions](../)
* فضا‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)