---
title: get_Justification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Absatzausrichtung Standardwert: CenteredAsGroup"
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() Methode


[Paragraph](../../../aspose.slides/paragraph/) Justification Standardwert: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Bemerkungen


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
* Bibliothek [Aspose.Slides](../../../)