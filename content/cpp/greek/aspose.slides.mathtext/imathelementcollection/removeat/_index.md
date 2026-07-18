---
title: RemoveAt()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.
type: docs
weight: 105
url: /el/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) μέθοδος

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## Δείτε επίσης

* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)