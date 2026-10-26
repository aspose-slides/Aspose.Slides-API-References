---
title: get_AnimateTransitions()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την επιλογή κίνησης μεταβάσεων. Ανάγνωση bool.
type: docs
weight: 1
url: /el/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() μέθοδος


Επιστρέφει την επιλογή κίνησης μεταβάσεων. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Δείτε επίσης

* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)