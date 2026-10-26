---
title: IndexOf()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει το ευρετήριο ενός συγκεκριμένου IMathBlock στη συλλογή.
type: docs
weight: 131
url: /el/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) μέθοδος

Καθορίζει το ευρετήριο ενός συγκεκριμένου [IMathBlock](../../imathblock/) στη συλλογή.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το στοιχείο προς εντοπισμό στη συλλογή. |

### Τιμή Επιστροφής

Το ευρετήριο του *mathBlock* εάν βρεθεί στη συλλογή· διαφορετικά, -1.

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)