---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's worden geëxporteerd.
type: docs
weight: 1
url: /nl/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() methode


Bepaalt of verborgen dia's worden geëxporteerd.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zie ook

* Klasse [IXamlOptions](../)
* Naamruimte [Aspose::Slides::Export::Xaml](../../)
* Bibliotheek [Aspose.Slides](../../../)