---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।
type: docs
weight: 1
url: /hi/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() विधि

निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## देखें

* कक्षा [XamlOptions](../)
* नामस्थान [Aspose::Slides::Export::Xaml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)