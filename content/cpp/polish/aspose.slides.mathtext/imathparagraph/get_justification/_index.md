---
title: get_Justification()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Justowanie akapitu Domyślna wartość: CenteredAsGroup"
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() metoda


[Paragraph](../../../aspose.slides/paragraph/) Justification Domyślna wartość: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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
* Klasa [IMathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)