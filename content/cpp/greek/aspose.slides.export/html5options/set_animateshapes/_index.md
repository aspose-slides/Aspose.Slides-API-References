---
title: set_AnimateShapes()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Ορίζει την επιλογή κίνησης των σχημάτων. Γράψτε bool.
type: docs
weight: 40
url: /el/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) μέθοδος

Ορίζει την επιλογή κίνησης των σχημάτων. Γράψτε **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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

* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)