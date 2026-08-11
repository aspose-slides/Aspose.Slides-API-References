---
title: get_Handout()
second_title: Aspose.Slides برای C++ API مرجع
description: مشخص می‌کند که چه تعداد اسلاید و به چه ترتیبی بر روی صفحه HandoutType قرار خواهند گرفت.
type: docs
weight: 1
url: /fa/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## متد HandoutLayoutingOptions::get_Handout() const

مشخص می‌کند که چه تعداد اسلاید و به چه ترتیبی روی صفحه قرار خواهند گرفت [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
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

## مراجع

* Enum [HandoutType](../../handouttype/)
* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)