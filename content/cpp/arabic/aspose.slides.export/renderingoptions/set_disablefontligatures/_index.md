---
title: set_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. عندما يتم ضبطها إلى true، سيتم تعطيل الروابط الحرفية في الناتج المعروض. بشكل افتراضي، يتم ضبط هذه الخاصية إلى false.
type: docs
weight: 53
url: /ar/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. عندما يتم ضبطه على **true**، سيتم تعطيل الروابط الحرفية في الناتج المعروض. بشكل افتراضي، يتم ضبط هذه الخاصية على **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // تعطيل الروابط الحرفية في عرض النص

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## انظر أيضًا

* فئة [RenderingOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)