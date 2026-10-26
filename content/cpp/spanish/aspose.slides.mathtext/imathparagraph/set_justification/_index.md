---
title: set_Justification()
second_title: Aspose.Slides para C++ Referencia de API
description: "Paragraph Justification Valor predeterminado: CenteredAsGroup"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) método


[Paragraph](../../../aspose.slides/paragraph/) Justification Valor predeterminado: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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
* Clase [IMathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)