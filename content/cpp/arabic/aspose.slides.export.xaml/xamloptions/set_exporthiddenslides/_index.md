---
title: set_ExportHiddenSlides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.
type: docs
weight: 14
url: /ar/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) طريقة

يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## انظر أيضًا

* فئة [XamlOptions](../)
* مساحة الاسم [Aspose::Slides::Export::Xaml](../../)
* مكتبة [Aspose.Slides](../../../)