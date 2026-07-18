---
title: IndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει το ευρετήριο ενός συγκεκριμένου IMathBlock στη συλλογή.
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) method

Καθορίζει το ευρετήριο ενός συγκεκριμένου [IMathBlock](../../imathblock/) στη συλλογή.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

### Τιμή Επιστροφής

Το ευρετήριο του *item* εάν βρεθεί στη συλλογή· διαφορετικά, -1.

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)