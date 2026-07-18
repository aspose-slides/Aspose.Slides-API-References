---
title: get_ExportHiddenSlides()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.
type: docs
weight: 1
url: /el/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() μέθοδος


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
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