---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides لمرجع API للغة C++
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.
type: docs
weight: 40
url: /ar/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) طريقة


يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## انظر أيضًا

* فئة [IGifOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)