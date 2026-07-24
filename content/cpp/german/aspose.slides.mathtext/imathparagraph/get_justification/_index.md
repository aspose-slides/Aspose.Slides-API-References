---
title: get_Justification()
second_title: Aspose.Slides für C++ API-Referenz
description: "Paragraph Justification Standardwert: CenteredAsGroup"
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() Methode

[Paragraph](../../../aspose.slides/paragraph/) Justification Standardwert: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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
* Klasse [IMathParagraph](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)