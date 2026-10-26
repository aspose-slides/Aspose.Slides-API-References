---
title: get_Justification()
second_title: Aspose.Slides per C++ Riferimento API
description: "Paragraph Justification Valore predefinito: CenteredAsGroup"
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() metodo


[Paragraph](../../../aspose.slides/paragraph/) Allineamento Valore predefinito: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Note


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
* Libreria [Aspose.Slides](../../../)