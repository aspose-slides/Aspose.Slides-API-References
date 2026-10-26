---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob versteckte Folien exportiert werden.
type: docs
weight: 1
url: /de/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() Methode


Bestimmt, ob versteckte Folien exportiert werden.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Hinweise



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Siehe auch

* Klasse [IXamlOptions](../)
* Namensraum [Aspose::Slides::Export::Xaml](../../)
* Bibliothek [Aspose.Slides](../../../)