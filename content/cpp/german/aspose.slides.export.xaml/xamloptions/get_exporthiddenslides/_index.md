---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob versteckte Folien exportiert werden.
type: docs
weight: 1
url: /de/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() Methode


Bestimmt, ob versteckte Folien exportiert werden.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Bemerkungen


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Siehe auch

* Klasse [XamlOptions](../)
* Namensraum [Aspose::Slides::Export::Xaml](../../)
* Bibliothek [Aspose.Slides](../../../)