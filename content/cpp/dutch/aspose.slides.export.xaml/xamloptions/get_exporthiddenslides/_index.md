---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's worden geëxporteerd.
type: docs
weight: 1
url: /nl/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() methode


Bepaalt of verborgen dia's worden geëxporteerd.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zie ook

* Klasse [XamlOptions](../)
* Naamruimte [Aspose::Slides::Export::Xaml](../../)
* Bibliotheek [Aspose.Slides](../../../)