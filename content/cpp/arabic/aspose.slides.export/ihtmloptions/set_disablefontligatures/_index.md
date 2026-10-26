---
title: set_DisableFontLigatures()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المربوطة. عند ضبطه على true، سيتم تعطيل الأحرف المربوطة في المخرجات المعروضة. بشكل افتراضي، تكون هذه الخاصية مضبوطة على false.
type: docs
weight: 196
url: /ar/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان النص يُظهر دون استخدام الأحرف المربوطة. عند ضبطه إلى **true**, سيتم تعطيل الأحرف المربوطة في الناتج المعروض. بشكل افتراضي، يتم ضبط هذه الخاصية إلى **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // تعطيل الأحرف المربوطة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## انظر أيضًا

* الفئة [IHtmlOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)