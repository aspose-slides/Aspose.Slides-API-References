---
title: set_Justification()
second_title: Aspose.Slides för C++ API-referens
description: "Paragrafsjustering Standardvärde: CenteredAsGroup"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) metod


[Paragraph](../../../aspose.slides/paragraph/) Justification Standardvärde: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Anmärkningar


Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Se också

* Enum [MathJustification](../../mathjustification/)
* Klass [IMathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)