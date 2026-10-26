---
title: set_DisableFontLigatures()
second_title: Aspose.Slides لـ C++ دليل واجهة برمجة التطبيقات
description: يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم ضبطها على true، سيتم تعطيل الأحرف المتصلة في ناتج العرض. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 144
url: /ar/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم ضبطها إلى **true**، سيتم تعطيل الأحرف المتصلة في ناتج العرض. بشكل افتراضي، تُضبط هذه الخاصية إلى **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
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

* الفئة [Html5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)