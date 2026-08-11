---
title: get_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينه إلى true، سيتم تعطيل الأحرف المتصلة في النتيجة المعروضة. بشكل افتراضي، تكون هذه الخاصية مُعينة إلى false.
type: docs
weight: 131
url: /ar/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() طريقة

يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينه إلى **true**، سيتم تعطيل الأحرف المتصلة في النتيجة المعروضة. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## انظر أيضًا

* الفئة [IHtml5Options](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)