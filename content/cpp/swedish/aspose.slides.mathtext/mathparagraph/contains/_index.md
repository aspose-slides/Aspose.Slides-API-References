---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om samlingen innehåller ett specifikt värde.
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) metod

Avgör om samlingen innehåller ett specifikt värde.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objektet att leta efter i samlingen. |

### Returvärde

true om *mathBlock* hittas i samlingen; annars false.
## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)