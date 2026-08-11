---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides لمرجع API للغة C++
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.
type: docs
weight: 40
url: /ar/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) طريقة

يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## انظر أيضاً

* الفئة [GifOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)