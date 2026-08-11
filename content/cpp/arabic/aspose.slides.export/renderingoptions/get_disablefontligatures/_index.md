---
title: get_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان النص يتم عرضه دون استخدام الروابط الأحرفية. عند تعيينها إلى true، سيتم تعطيل الروابط الأحرفية في الناتج المعروض. بشكل افتراضي، يتم تعيين هذه الخاصية إلى false.
type: docs
weight: 40
url: /ar/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() طريقة

يحصل على قيمة تشير إلى ما إذا كان النص يتم عرضه دون استخدام الروابط الأحرفية. عندما يتم تعيينها إلى **true**، سيتم تعطيل الروابط الأحرفية في الناتج المعروض. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // تعطيل الروابط الأحرفية في عرض النص

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## انظر أيضًا

* فئة [RenderingOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)