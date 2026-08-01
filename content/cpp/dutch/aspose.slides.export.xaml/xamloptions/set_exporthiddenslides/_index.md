---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's worden geëxporteerd.
type: docs
weight: 14
url: /nl/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) methode


Bepaalt of verborgen dia's worden geëxporteerd.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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