---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση IMathElement.
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) μέθοδος

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που ξεκινά από το μηδέν του στοιχείου που θα ληφθεί |

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)