---
title: set_Justification()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Justowanie akapitu Domyślna wartość: CenteredAsGroup"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) metoda

[Paragraph](../../../aspose.slides/paragraph/) Justification Domyślna wartość: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Uwagi

Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Zobacz także

* Enum [MathJustification](../../mathjustification/)
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)