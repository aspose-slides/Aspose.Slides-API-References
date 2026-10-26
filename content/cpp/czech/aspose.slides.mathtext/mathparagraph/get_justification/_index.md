---
title: get_Justification()
second_title: Aspose.Slides pro C++ referenční API
description: "Paragraph Justification Výchozí hodnota: CenteredAsGroup"
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() metoda


[Paragraph](../../../aspose.slides/paragraph/) Justification Výchozí hodnota: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Poznámky


Příklad: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Viz také

* Enum [MathJustification](../../mathjustification/)
* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)