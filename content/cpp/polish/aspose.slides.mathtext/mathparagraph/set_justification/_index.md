---
title: set_Justification()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Justowanie akapitu Domyślna wartość: CenteredAsGroup"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) metoda


[Paragraph](../../../aspose.slides/paragraph/) Justowanie Domyślna wartość: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)