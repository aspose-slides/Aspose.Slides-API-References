---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.
type: docs
weight: 14
url: /tr/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metodu

Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Ayrıca bakınız

* Sınıf [IXamlOptions](../)
* Ad alanı [Aspose::Slides::Export::Xaml](../../)
* Kütüphane [Aspose.Slides](../../../)