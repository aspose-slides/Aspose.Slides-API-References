---
title: get_Justification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Paragraph Justification Valor predeterminado: CenteredAsGroup"
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() método


[Paragraph](../../../aspose.slides/paragraph/) Justificación Valor predeterminado: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Observaciones


Ejemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Ver también

* Enumeración [MathJustification](../../mathjustification/)
* Clase [MathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)