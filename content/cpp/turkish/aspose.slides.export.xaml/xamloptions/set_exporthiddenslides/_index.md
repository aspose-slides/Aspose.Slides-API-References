---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.
type: docs
weight: 14
url: /tr/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metot


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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
* İsim Alanı [Aspose::Slides::Export::Xaml](../../)
* Kütüphane [Aspose.Slides](../../../)