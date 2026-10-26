---
title: set_Justification()
second_title: Aspose.Slides C++ API Referencia
description: "Bekezdés igazítás alapértelmezett érték: CenteredAsGroup"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) metódus


[Paragraph](../../../aspose.slides/paragraph/) Igazítás Alapértelmezett érték: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Megjegyzések


Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Lásd még

* Enum [MathJustification](../../mathjustification/)
* Osztály [MathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)