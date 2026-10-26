---
title: set_ExportHiddenSlides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.
type: docs
weight: 14
url: /ar/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) طريقة


يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## انظر أيضًا

* الفئة [IXamlOptions](../)
* النطاق [Aspose::Slides::Export::Xaml](../../)
* المكتبة [Aspose.Slides](../../../)