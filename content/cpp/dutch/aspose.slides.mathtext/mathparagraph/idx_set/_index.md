---
title: idx_set()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het item op op de opgegeven index. Alleen-lezen IMathBlock.
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/mathparagraph/idx_set/
---
## MathParagraph::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) methode

Haalt het item op op de opgegeven index. Alleen-lezen [IMathBlock](../../imathblock/).

```cpp
void Aspose::Slides::MathText::MathParagraph::idx_set(int32_t index, System::SharedPtr<IMathBlock> value) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het item om op te halen |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het blok van een wiskundige tekst. |
## Opmerkingen



Voorbeeld: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [MathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)