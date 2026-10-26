---
title: set_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم تعيينها إلى true، يتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، يتم تعيين هذه الخاصية إلى false.
type: docs
weight: 339
url: /ar/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) طريقة

يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما يتم ضبطها على **true**، سيتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## انظر أيضًا

* الفئة [ISVGOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)