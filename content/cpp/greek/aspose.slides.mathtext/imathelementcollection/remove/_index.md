---
title: Remove()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.
type: docs
weight: 92
url: /el/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) μέθοδος

Αφαιρέει την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

### Τιμή Επιστροφής

true εάν *item* αφαιρέθηκε επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν *item* δεν βρεθεί στην αρχική συλλογή.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)