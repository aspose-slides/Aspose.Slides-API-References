---
title: set_Justification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Paragraph Justification Standaardwaarde: CenteredAsGroup"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) methode

[Paragraph](../../../aspose.slides/paragraph/) Justification Standaardwaarde: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* Bibliotheek [Aspose.Slides](../../../)