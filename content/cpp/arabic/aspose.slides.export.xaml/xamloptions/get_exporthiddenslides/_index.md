---
title: get_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.
type: docs
weight: 1
url: /ar/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() طريقة

يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## انظر أيضًا

* الفئة [XamlOptions](../)
* المجال [Aspose::Slides::Export::Xaml](../../)
* المكتبة [Aspose.Slides](../../../)