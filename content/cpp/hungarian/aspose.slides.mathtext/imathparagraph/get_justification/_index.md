---
title: get_Justification()
second_title: Aspose.Slides for C++ API referenciája
description: "Bekezdés igazítás Alapértelmezett érték: CenteredAsGroup"
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() metódus


[Paragraph](../../../aspose.slides/paragraph/) Justification Alapértelmezett érték: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Megjegyzések


Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Lásd még

* Enumeráció [MathJustification](../../mathjustification/)
* Osztály [IMathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)