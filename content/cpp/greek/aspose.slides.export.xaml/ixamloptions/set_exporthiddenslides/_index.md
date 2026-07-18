---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.
type: docs
weight: 14
url: /el/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) μέθοδος


Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Δείτε επίσης

* Κλάση [IXamlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export::Xaml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)