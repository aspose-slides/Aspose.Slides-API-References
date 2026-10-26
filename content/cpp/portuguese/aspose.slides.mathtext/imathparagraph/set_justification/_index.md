---
title: set_Justification()
second_title: Referência da API Aspose.Slides para C++
description: "Justificação de Parágrafo Valor padrão: CenteredAsGroup"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) método

[Paragraph](../../../aspose.slides/paragraph/) Justificação Valor padrão: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Observações

Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Ver também

* Enumeração [MathJustification](../../mathjustification/)
* Classe [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)