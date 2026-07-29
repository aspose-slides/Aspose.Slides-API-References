---
title: Clear()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla element från samlingen.
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metod


Tar bort alla element från samlingen.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Anmärkningar


Exempel:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Se även

* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)