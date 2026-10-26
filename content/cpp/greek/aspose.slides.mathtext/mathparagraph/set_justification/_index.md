---
title: set_Justification()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: "Στοίχιση παραγράφου Τιμή προεπιλογής: CenteredAsGroup"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) μέθοδος


[Paragraph](../../../aspose.slides/paragraph/) Justification Τιμή προεπιλογής: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Δείτε επίσης

* Enum [MathJustification](../../mathjustification/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)