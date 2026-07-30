---
title: set_Justification()
second_title: Riferimento API Aspose.Slides per C++
description: "Paragraph Justification Valore predefinito: CenteredAsGroup"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) metodo


[Paragraph](../../../aspose.slides/paragraph/) Justification Valore predefinito: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Osservazioni


Esempio:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Vedi anche

* Enum [MathJustification](../../mathjustification/)
* Classe [MathParagraph](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)