---
title: Contains()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) μέθοδος


Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το αντικείμενο που πρέπει να εντοπιστεί στη συλλογή. |

### Τιμή Επιστροφής

αληθής εάν το *item* βρεθεί στη συλλογή· διαφορετικά, ψευδής.
## Σχόλια



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathBlockCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)