---
title: RemoveAt()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί ένα στοιχείο στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) μέθοδος


Αφαιρεί ένα στοιχείο στη συγκεκριμένη θέση της συλλογής.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. |
## Σχόλια



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Δείτε επίσης

* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)