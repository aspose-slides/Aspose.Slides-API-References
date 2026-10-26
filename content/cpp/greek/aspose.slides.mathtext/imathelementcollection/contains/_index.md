---
title: Contains()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) μέθοδος


Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το αντικείμενο προς εντοπισμό στη συλλογή. |

### Τιμή Επιστροφής

true εάν το *item* βρεθεί στη συλλογή· διαφορετικά, false.
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* κλάση [IMathElement](../../imathelement/)
* κλάση [IMathElementCollection](../)
* χώρος ονομάτων [Aspose::Slides::MathText](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)