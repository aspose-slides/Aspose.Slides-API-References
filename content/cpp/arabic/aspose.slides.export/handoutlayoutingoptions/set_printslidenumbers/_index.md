---
title: set_PrintSlideNumbers()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كان يجب طباعة أرقام الشرائح المعروضة أم لا.
type: docs
weight: 40
url: /ar/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) طريقة

يحدد ما إذا كان يجب طباعة أرقام الشرائح المعروضة أم لا.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## ملاحظات

القيمة الافتراضية هي **true**. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## انظر أيضًا

* الفئة [HandoutLayoutingOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)