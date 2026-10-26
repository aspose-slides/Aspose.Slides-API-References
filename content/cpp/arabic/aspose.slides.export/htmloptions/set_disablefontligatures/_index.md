---
title: set_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينه إلى true، سيتم تعطيل الحروف المتصلة في الناتج المعروض. بشكل افتراضي، تكون هذه الخاصية مُعيَّنة إلى false.
type: docs
weight: 105
url: /ar/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) طريقة


يعين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينه إلى **true**, سيتم تعطيل الحروف المتصلة في الناتج المعروض. بشكل افتراضي, تكون هذه الخاصية مُعيَّنة إلى **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // تعطيل الحروف المتصلة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## انظر أيضًا

* فئة [HtmlOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)