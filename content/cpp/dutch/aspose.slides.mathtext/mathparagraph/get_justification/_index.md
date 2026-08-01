---
title: get_Justification()
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Uitlijning van alinea Standaardwaarde: CenteredAsGroup"
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() methode

[Paragraph](../../../aspose.slides/paragraph/) Justification Standaardwaarde: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
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
* Klasse [MathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)