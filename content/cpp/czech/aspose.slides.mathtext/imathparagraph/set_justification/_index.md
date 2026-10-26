---
title: set_Justification()
second_title: Aspose.Slides pro C++ API Reference
description: "Paragraph Justification Výchozí hodnota: CenteredAsGroup"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) metoda


[Paragraph](../../../aspose.slides/paragraph/) Justification Výchozí hodnota: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Poznámky


Příklad:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Viz také

* Výčet [MathJustification](../../mathjustification/)
* Třída [IMathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)