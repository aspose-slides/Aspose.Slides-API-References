---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.
type: docs
weight: 14
url: /el/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) μέθοδος


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Δείτε επίσης

* Κλάση [XamlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export::Xaml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)