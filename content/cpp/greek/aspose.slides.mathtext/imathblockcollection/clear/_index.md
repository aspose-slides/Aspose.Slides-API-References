---
title: Clear()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί όλα τα στοιχεία από τη συλλογή.
type: docs
weight: 118
url: /el/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() μέθοδος


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Δείτε επίσης

* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)