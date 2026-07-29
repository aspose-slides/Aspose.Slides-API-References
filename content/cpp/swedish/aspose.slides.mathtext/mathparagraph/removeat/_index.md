---
title: RemoveAt()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort ett objekt på det angivna indexet i samlingen.
type: docs
weight: 157
url: /sv/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metod


Tar bort ett objekt på det angivna indexet i samlingen.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för objektet som ska tas bort. |
## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Se även

* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)