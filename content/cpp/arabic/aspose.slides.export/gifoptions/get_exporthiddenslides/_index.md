---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.
type: docs
weight: 27
url: /ar/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() طريقة


يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## انظر أيضًا

* فئة [GifOptions](../)
* مساحة الأسماء [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)