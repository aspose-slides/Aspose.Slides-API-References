---
title: set_AnimateShapes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει την επιλογή κίνησης σχημάτων. Γράψτε bool.
type: docs
weight: 40
url: /el/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) μέθοδος


Ορίζει την επιλογή κίνησης σχημάτων. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Παρατηρήσεις


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