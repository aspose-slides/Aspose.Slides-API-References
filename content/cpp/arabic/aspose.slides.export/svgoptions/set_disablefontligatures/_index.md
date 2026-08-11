---
title: set_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضبط قيمة تشير إلى ما إذا تم عرض النص دون استخدام الربط. عندما يتم ضبطها على true، سيتم تعطيل الربط في المخرجات المعروضة. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 339
url: /ar/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) الطريقة


يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الربط. عند الضبط على **true**, سيتم تعطيل الربط في الناتج المعروض. بشكلٍ افتراضي, تُضبط هذه الخاصية على **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // تعطيل الربط في عرض النص

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## انظر أيضًا

* الفئة [SVGOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)