---
title: set_Justification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Paragraph Justification Standardwert: CenteredAsGroup"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) Methode


[Paragraph](../../../aspose.slides/paragraph/) Justification Standardwert: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Hinweise


Beispiel:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Siehe auch

* Enum [MathJustification](../../mathjustification/)
* Klasse [MathParagraph](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)