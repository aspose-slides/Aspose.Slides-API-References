---
title: Clear()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle elementen uit de collectie.
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() methode


Verwijdert alle elementen uit de collectie.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Zie ook

* Klasse [MathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)