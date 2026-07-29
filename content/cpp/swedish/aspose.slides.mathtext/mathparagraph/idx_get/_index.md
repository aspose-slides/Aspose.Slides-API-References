---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar föremålet på det angivna indexet. Skrivskyddad IMathBlock.
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) metod


Hämtar föremålet på det angivna indexet. Skrivskyddad [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för föremålet som ska hämtas |

### Returvärde

Blocket för en matematisk text.
## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Se också

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)