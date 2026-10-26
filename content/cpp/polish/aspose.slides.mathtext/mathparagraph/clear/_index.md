---
title: Clear()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Usuwa wszystkie elementy z kolekcji.
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metoda


Usuwa wszystkie elementy z kolekcji.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Uwagi


Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Zobacz także

* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)