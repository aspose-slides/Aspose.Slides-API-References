---
title: get_ExportHiddenSlides()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।
type: docs
weight: 1
url: /hi/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() विधि


निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## देखें

* क्लास [IXamlOptions](../)
* नेमस्पेस [Aspose::Slides::Export::Xaml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)