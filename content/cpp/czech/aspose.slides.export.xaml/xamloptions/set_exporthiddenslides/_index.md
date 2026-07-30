---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Určuje, zda budou skryté snímky exportovány.
type: docs
weight: 14
url: /cs/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metoda


Určuje, zda budou skryté snímky exportovány.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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