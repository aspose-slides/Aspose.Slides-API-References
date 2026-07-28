---
title: Clear()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja az összes elemet a gyűjteményből.
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metódus


Eltávolítja az összes elemet a gyűjteményből.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Megjegyzések


Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Lásd még

* Osztály [MathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)