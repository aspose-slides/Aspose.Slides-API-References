---
title: Clear()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt alle Elemente aus der Sammlung.
type: docs
weight: 79
url: /de/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() Methode

Entfernt alle Elemente aus der Sammlung.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Hinweise

Beispiel:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Siehe auch

* Klasse [MathParagraph](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)