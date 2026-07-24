---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.
type: docs
weight: 1
url: /tr/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() yöntemi

Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Açıklamalar


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```



## Ayrıca Bakınız

* Sınıf [XamlOptions](../)
* Ad alanı [Aspose::Slides::Export::Xaml](../../)
* Kütüphane [Aspose.Slides](../../../)