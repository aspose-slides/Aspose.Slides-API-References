---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि छुपी स्लाइड्स निर्यात की जाएँगी या नहीं।
type: docs
weight: 14
url: /hi/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) विधि


निर्धारित करता है कि छुपी स्लाइड्स निर्यात की जाएँगी या नहीं।

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## देखें

* वर्ग [IXamlOptions](../)
* नामस्थान [Aspose::Slides::Export::Xaml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)