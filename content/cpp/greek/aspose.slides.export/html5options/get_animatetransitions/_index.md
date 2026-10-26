---
title: get_AnimateTransitions()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την επιλογή κίνησης μεταβάσεων. Ανάγνωση bool.
type: docs
weight: 1
url: /el/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() μέθοδος


Επιστρέφει την επιλογή κίνησης μεταβάσεων. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)