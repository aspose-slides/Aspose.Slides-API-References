---
title: Clear()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Odstraňuje všechny prvky ze sbírky.
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metoda


Odstraní všechny prvky ze sbírky.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Poznámky


Příklad: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Viz také

* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)