---
title: get_Justification()
second_title: Αναφορά API Aspose.Slides για C++
description: "Στοίχηση παραγράφου Προεπιλεγμένη τιμή: CenteredAsGroup"
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() μέθοδος


[Paragraph](../../../aspose.slides/paragraph/) Στοίχηση Προεπιλεγμένη τιμή: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Δείτε επίσης

* Απαρίθμηση [MathJustification](../../mathjustification/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)