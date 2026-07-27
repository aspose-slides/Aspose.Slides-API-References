---
title: set_Justification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Paragraph Justification Valor predeterminado: CenteredAsGroup"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) método

[Paragraph](../../../aspose.slides/paragraph/) Justificación Valor predeterminado: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Observaciones

Ejemplo:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Ver también

* Enum [MathJustification](../../mathjustification/)
* Clase [MathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)