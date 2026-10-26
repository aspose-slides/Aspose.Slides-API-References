---
title: get_AnimateShapes()
second_title: Aspose.Slides για C++ API Reference
description: Επιστρέφει την επιλογή κίνησης σχημάτων. Ανάγνωση bool.
type: docs
weight: 27
url: /el/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() μέθοδος


Επιστρέφει την επιλογή κίνησης σχημάτων. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Σημειώσεις


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