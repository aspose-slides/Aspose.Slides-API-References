---
title: JoinBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een ander wiskundig blok toe aan dit blok
type: docs
weight: 196
url: /nl/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) methode


Voegt een ander wiskundig blok toe aan dit blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het te verbinden blok |

### Retourwaarde

dit wiskundige blok na het samenvoegen
## Opmerkingen



Voorbeeld: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [MathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)