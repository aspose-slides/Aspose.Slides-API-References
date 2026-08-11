---
title: set_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينها إلى true، يتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 53
url: /ar/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينها إلى **true**، سيتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، تُ ضبط هذه الخاصية على **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
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