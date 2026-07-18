---
title: IndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει το ευρετήριο ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή.
type: docs
weight: 144
url: /el/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) μέθοδος

Καθορίζει το ευρετήριο ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το στοιχείο προς εντοπισμό στη συλλογή. |

### Τιμή Επιστροφής

Το ευρετήριο του *item*  εάν βρεθεί στη συλλογή· διαφορετικά, -1.

## Παρατηρήσεις



Παράδειγμα:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)