---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides للـ C++
description: تحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط اللغوية. عندما يتم ضبطها على true، سيتم تعطيل الروابط اللغوية في الناتج المعروض. بشكل افتراضي، تُضبط هذه الخاصية على false.
type: docs
weight: 326
url: /ar/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() طريقة


يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط اللغوية. عند ضبطه على **true**، ستُعطل الروابط اللغوية في الناتج المعروض. بشكل افتراضي، تُضبط هذه الخاصية على **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // تعطيل الروابط اللغوية في عرض النص

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## انظر أيضًا

* الفئة [ISVGOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)