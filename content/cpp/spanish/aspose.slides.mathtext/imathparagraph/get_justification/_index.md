---
title: get_Justification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Justificación de párrafo Valor predeterminado: CenteredAsGroup"
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() método


[Paragraph](../../../aspose.slides/paragraph/) Justification Valor predeterminado: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Comentarios


Ejemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Véase también

* Enumeración [MathJustification](../../mathjustification/)
* Clase [IMathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)