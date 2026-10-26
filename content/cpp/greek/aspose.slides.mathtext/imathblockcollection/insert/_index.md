---
title: Insert()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Εισάγει το IMathBlock στη συλλογή στο καθορισμένο δείκτη.
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) μέθοδος


Εισάγει [IMathBlock](../../imathblock/) στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στον οποίο πρέπει να εισαχθεί ένα στοιχείο. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το [IMathBlock](../../imathblock/) προς εισαγωγή. |
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)