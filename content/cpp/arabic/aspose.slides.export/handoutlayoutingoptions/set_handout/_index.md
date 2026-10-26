---
title: set_Handout()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد عدد الشرائح وبأي تسلسل سيتم وضعها على الصفحة HandoutType.
type: docs
weight: 14
url: /ar/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) طريقة


يحدد عدد الشرائح وبأي تسلسل ستوضع على الصفحة [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## ملاحظات


القيمة الافتراضية هي **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

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

## انظر أيضًا

* تعداد [HandoutType](../../handouttype/)
* فئة [HandoutLayoutingOptions](../)
* نطاق الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)