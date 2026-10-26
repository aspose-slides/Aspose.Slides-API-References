---
title: set_Justification()
second_title: Referência da API Aspose.Slides para C++
description: "Paragraph Justificação Valor padrão: CenteredAsGroup"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) método

[Paragraph](../../../aspose.slides/paragraph/) Justification Valor padrão: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* Library [Aspose.Slides](../../../)