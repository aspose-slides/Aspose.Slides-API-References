---
title: set_DisableFontLigatures()
second_title: مرجع API Aspose.Slides للغة C++
description: تحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى true، يتم تعطيل الأحرف المتصلة في الإخراج المعروض. بشكل افتراضي، تكون هذه الخاصية مُعينة إلى false.
type: docs
weight: 144
url: /ar/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) طريقة

تحدد قيمة تشير إلى ما إذا كان سيتم عرض النص دون استخدام الحروف المتصلة. عند تعيينها إلى **true**، سيتم تعطيل الحروف المتصلة في الإخراج المعروض. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // تعطيل الحروف المتصلة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## انظر أيضا

* فئة [IHtml5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)