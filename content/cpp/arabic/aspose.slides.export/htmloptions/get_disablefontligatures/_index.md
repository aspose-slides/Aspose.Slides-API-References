---
title: get_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينه إلى true، سيتم تعطيل الأحرف المتصلة في النتيجة المعروضة. بشكل افتراضي، تُعيّن هذه الخاصية إلى false.
type: docs
weight: 92
url: /ar/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() طريقة


يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينه إلى **true**، سيتم تعطيل الأحرف المتصلة في النتيجة المعروضة. بشكل افتراضي، تُعيّن هذه الخاصية إلى **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## انظر أيضًا

* الفئة [HtmlOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)