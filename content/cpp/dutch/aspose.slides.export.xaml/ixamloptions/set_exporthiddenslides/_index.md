---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's geëxporteerd zullen worden.
type: docs
weight: 14
url: /nl/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) methode


Bepaalt of verborgen dia's geëxporteerd zullen worden.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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