---
title: set_Justification()
second_title: Aspose.Slides a C++ API hivatkozás
description: "Bekezdés igazítása Alapértelmezett érték: CenteredAsGroup"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) metódus

[Paragraph](../../../aspose.slides/paragraph/) Justification Alapértelmezett érték: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)