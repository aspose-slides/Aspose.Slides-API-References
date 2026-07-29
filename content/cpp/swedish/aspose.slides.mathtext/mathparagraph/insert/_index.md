---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar IMathBlock i samlingen på det angivna indexet.
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) metod


Infogar [IMathBlock](../../imathblock/) i samlingen på det angivna indexet.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där ett objekt ska infogas. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Den [IMathBlock](../../imathblock/) att infoga. |
## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## Se också

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)