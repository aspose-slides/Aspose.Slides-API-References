---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob ausgeblendete Folien exportiert werden.
type: docs
weight: 14
url: /de/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) Methode


Bestimmt, ob ausgeblendete Folien exportiert werden.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Anmerkungen



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