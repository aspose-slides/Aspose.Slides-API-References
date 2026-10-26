---
title: idx_set()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση IMathBlock.
type: docs
weight: 105
url: /el/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) μέθοδος

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που αρχίζει από το μηδέν του στοιχείου που θα ληφθεί |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το μπλοκ ενός μαθηματικού κειμένου. |
## Σχόλια



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)