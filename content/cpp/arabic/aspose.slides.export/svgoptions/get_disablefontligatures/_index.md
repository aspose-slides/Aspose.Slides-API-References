---
title: get_DisableFontLigatures()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعطي قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الربط. عند تعيينه إلى true، سيتم تعطيل الربط في المخرجات المعروضة. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 326
url: /ar/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() طريقة

يعطي قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الربط. عند تعيينه إلى **true**، سيتم تعطيل الربط في المخرجات المعروضة. بشكل افتراضي، يتم تعيين هذه الخاصية إلى **false**.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
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

* فئة [SVGOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)