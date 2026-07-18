---
title: set_Justification()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Στοίχιση παραγράφου Προεπιλεγμένη τιμή: CenteredAsGroup"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) μέθοδος

[Paragraph](../../../aspose.slides/paragraph/) Στοίχιση Προεπιλεγμένη τιμή: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)