---
title: set_Justification()
second_title: Aspose.Slides för C++ API-referens
description: "Paragraph Justering Standardvärde: CenteredAsGroup"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) metod


[Paragraph](../../../aspose.slides/paragraph/) Justering Standardvärde: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Anmärkningar


Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Se även

* Enum [MathJustification](../../mathjustification/)
* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)