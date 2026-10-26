---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.
type: docs
weight: 1
url: /el/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() method


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
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