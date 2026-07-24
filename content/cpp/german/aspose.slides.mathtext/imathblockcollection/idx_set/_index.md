---
title: idx_set()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Element am angegebenen Index ab. Nur lesend IMathBlock.
type: docs
weight: 105
url: /de/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) Methode


Ruft das Element am angegebenen Index ab. Nur lesend [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index des abzurufenden Elements |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Der Block eines mathematischen Textes. |
## Anmerkungen



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)