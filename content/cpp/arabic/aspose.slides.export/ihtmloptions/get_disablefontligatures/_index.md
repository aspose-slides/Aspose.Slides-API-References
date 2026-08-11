---
title: get_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان النص يُعرض بدون استخدام الروابط الحروفية. عندما يضبط إلى true، سيتم تعطيل الروابط الحروفية في المخرجات المعروضة. بشكل افتراضي، يتم ضبط هذه الخاصية على false.
type: docs
weight: 183
url: /ar/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() طريقة


يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحروفية. عندما يتم تعيينها إلى **true**، ستُعطل الروابط الحروفية في الناتج المعروض. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // تعطيل الروابط الحروفية في عرض النص

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## انظر أيضًا

* الفئة [IHtmlOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)