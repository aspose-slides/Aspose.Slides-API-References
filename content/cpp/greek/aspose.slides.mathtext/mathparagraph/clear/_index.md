---
title: Clear()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αφαιρεί όλα τα στοιχεία από τη συλλογή.
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() μέθοδος


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Δείτε επίσης

* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)