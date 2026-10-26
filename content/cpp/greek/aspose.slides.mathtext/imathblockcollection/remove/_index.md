---
title: Remove()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή/>.
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) μέθοδος

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

### Τιμή Επιστροφής

true εάν το *item* αφαιρέθηκε με επιτυχία από τη συλλογή· διαφορετικά, false. Η μέθοδος αυτή επίσης επιστρέφει false εάν το *item* δεν βρέθηκε στην αρχική συλλογή/>.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)