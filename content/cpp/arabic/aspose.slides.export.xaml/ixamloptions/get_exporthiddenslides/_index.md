---
title: get_ExportHiddenSlides()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدّد ما إذا كانت الشرائح المخفيّة سيتم تصديرها.
type: docs
weight: 1
url: /ar/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() طريقة


تحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## انظر أيضًا

* فئة [IXamlOptions](../)
* نطاق [Aspose::Slides::Export::Xaml](../../)
* مكتبة [Aspose.Slides](../../../)