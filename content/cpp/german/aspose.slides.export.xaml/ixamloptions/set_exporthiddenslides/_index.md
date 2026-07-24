---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob verborgene Folien exportiert werden.
type: docs
weight: 14
url: /de/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) Methode


Bestimmt, ob verborgene Folien exportiert werden.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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