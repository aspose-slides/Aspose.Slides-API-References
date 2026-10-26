---
title: get_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عندما تُضبط على true، سيتم تعطيل الحروف المتصلة في الإخراج المعروض. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 131
url: /ar/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() طريقة

يحصل على قيمة تشير إلى ما إذا كان النص يتم عرضه دون استخدام الحروف المترابطة. عندما يتم تعيينها إلى **true**، سيتم تعطيل الحروف المترابطة في الناتج المعروض. بشكل افتراضي، تُعيَّن هذه الخاصية إلى **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // تعطيل الحروف المتصلة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## انظر أيضًا

* الفئة [Html5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)