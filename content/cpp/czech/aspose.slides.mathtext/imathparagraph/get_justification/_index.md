---
title: get_Justification()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Paragraph Justification Výchozí hodnota: CenteredAsGroup"
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() metoda

[Paragraph](../../../aspose.slides/paragraph/) Justification Výchozí hodnota: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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