---
title: set_AnimateTransitions()
second_title: Aspose.Slides για την αναφορά API C++
description: Ορίζει την επιλογή κίνησης μεταβάσεων. Γράψτε bool.
type: docs
weight: 14
url: /el/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) μέθοδος

Ορίζει την επιλογή κίνησης μεταβάσεων. Γράψτε **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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