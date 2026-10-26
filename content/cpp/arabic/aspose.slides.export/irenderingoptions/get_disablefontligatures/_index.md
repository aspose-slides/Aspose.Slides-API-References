---
title: get_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم ضبطها على true، سيتم تعطيل الأحرف المتصلة في الناتج المعروض. افتراضيًا، يتم تعيين هذه الخاصية إلى false.
type: docs
weight: 40
url: /ar/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() طريقة

يقوم بالحصول على قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى **true**، سيتم تعطيل الأحرف المتصلة في الناتج المعروض. افتراضيًا، يتم تعيين هذه الخاصية إلى **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## انظر أيضًا

* فئة [IRenderingOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)