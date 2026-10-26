---
title: get_Justification()
second_title: Aspose.Slides för C++ API-referens
description: "Paragraph Justification Standardvärde: CenteredAsGroup"
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() metod


[Paragraph](../../../aspose.slides/paragraph/) Justering Standardvärde: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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
* Klass [IMathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)