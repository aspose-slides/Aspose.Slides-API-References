---
title: get_Justification()
second_title: Aspose.Slides C++ API referencia
description: "Paragraph Justification alapértelmezett érték: CenteredAsGroup"
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() metódus


[Paragraph](../../../aspose.slides/paragraph/) Igazítás Alapértelmezett érték: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Megjegyzések


Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Lásd még

* Felsoroló [MathJustification](../../mathjustification/)
* Osztály [MathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)