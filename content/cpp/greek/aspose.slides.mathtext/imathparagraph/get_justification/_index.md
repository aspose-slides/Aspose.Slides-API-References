---
title: get_Justification()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Paragraph Justification Προεπιλεγμένη τιμή: CenteredAsGroup"
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() μέθοδος

[Paragraph](../../../aspose.slides/paragraph/) Justification Τιμή προεπιλογής: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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
* Κλάση [IMathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)