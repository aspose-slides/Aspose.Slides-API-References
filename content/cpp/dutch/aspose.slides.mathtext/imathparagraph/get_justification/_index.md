---
title: get_Justification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Paragraph Justification Standaardwaarde: CenteredAsGroup"
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() methode


[Paragraph](../../../aspose.slides/paragraph/) Justification Standaardwaarde: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Zie ook

* Enum [MathJustification](../../mathjustification/)
* Klasse [IMathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)