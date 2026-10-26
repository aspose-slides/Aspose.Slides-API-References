---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer indexet för ett specifikt IMathBlock i samlingen.
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) metod


Bestämmer indexet för ett specifikt [IMathBlock](../../imathblock/) i samlingen.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objektet att leta upp i samlingen. |

### Returvärde

Indexet för *mathBlock*  om det finns i samlingen; annars -1.
## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [MathParagraph](../)
* Namnrum [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)