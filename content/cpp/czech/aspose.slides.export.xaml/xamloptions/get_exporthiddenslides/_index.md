---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda budou skryté snímky exportovány.
type: docs
weight: 1
url: /cs/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metoda


Určuje, zda budou skryté snímky exportovány.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Viz také

* Třída [XamlOptions](../)
* Jmenný prostor [Aspose::Slides::Export::Xaml](../../)
* Knihovna [Aspose.Slides](../../../)