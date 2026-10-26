---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index eines bestimmten IMathBlock in der Sammlung.
type: docs
weight: 131
url: /de/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) Methode


Bestimmt den Index eines bestimmten [IMathBlock](../../imathblock/) in der Sammlung.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Das Element, das in der Sammlung gefunden werden soll. |

### Rückgabewert

Der Index von *mathBlock*, wenn er in der Sammlung gefunden wird; andernfalls -1.
## Anmerkungen



Beispiel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [MathParagraph](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)