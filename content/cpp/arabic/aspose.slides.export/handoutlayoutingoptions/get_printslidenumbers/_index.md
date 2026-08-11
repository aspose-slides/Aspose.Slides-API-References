---
title: get_PrintSlideNumbers()
second_title: مرجع API ل Aspose.Slides للـ C++
description: يحدد ما إذا كان يجب طباعة أرقام الشرائح المعروضة أم لا.
type: docs
weight: 27
url: /ar/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const طريقة

يحدد ما إذا كان ينبغي طباعة أرقام الشرائح المعروضة أم لا.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
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

## راجع أيضًا

* الفئة [HandoutLayoutingOptions](../)
* المساحة الاسمية [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)