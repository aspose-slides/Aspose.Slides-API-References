---
title: idx_set()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar objektet på det angivna indexet. Skrivskyddad IMathBlock.
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) metod

Hämtar objektet på det angivna indexet. Skrivskyddad [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för objektet som ska hämtas |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Blocket för en matematisk text. |
## Anmärkningar

Exempel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathBlockCollection](../)
* Namnutrymme [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)