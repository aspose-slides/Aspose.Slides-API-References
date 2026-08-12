---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात की जाएँगी।
type: docs
weight: 14
url: /hi/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) विधि


निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात की जाएँगी।

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## संबंधित देखें

* क्लास [XamlOptions](../)
* नामस्थान [Aspose::Slides::Export::Xaml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)