---
title: get_Justification()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Paragraph Justification Domyślna wartość: CenteredAsGroup"
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() metoda

[Paragraph](../../../aspose.slides/paragraph/) Justification Domyślna wartość: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Uwagi

Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Zobacz także

* Wyliczenie [MathJustification](../../mathjustification/)
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)