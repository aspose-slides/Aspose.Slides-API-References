---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.
type: docs
weight: 1
url: /tr/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() metodu


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## İlgili

* Sınıf [IXamlOptions](../)
* Ad Alanı [Aspose::Slides::Export::Xaml](../../)
* Kütüphane [Aspose.Slides](../../../)