---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.
type: docs
weight: 27
url: /ar/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() طريقة


يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
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