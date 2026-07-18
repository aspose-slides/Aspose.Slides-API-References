---
title: IndexOf()
second_title: Aspose.Slides για C++ API Reference
description: Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου μαθηματικού τύπου στη συλλογή.
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) μέθοδος

Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου μαθηματικού τύπου στη συλλογή.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το στοιχείο που πρέπει να εντοπιστεί στη συλλογή. |

### Τιμή επιστροφής

Ο δείκτης του *item* εάν βρεθεί στη συλλογή· διαφορετικά, -1.
## Σχόλια



Παράδειγμα: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)