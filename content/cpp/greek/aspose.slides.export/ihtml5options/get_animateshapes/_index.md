---
title: get_AnimateShapes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει επιλογή κίνησης σχημάτων. Ανάγνωση bool.
type: docs
weight: 27
url: /el/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() μέθοδος


Επιστρέφει επιλογή κίνησης σχημάτων. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Σχόλια


Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Δείτε επίσης

* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)