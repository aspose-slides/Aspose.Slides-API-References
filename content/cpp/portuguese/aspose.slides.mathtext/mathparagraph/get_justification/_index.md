---
title: get_Justification()
second_title: Referência da API Aspose.Slides for C++
description: "Justificação de Parágrafo Valor padrão: CenteredAsGroup"
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() método


[Paragraph](../../../aspose.slides/paragraph/) Justification Valor padrão: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Observações


Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Veja também

* Enum [MathJustification](../../mathjustification/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)