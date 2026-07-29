---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till IMathBlock i slutet av samlingen.
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) metod

Lägger till [IMathBlock](../../imathblock/) i slutet av samlingen.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Ett matematiskt block som kommer att läggas till i slutet av samlingen |
## Anmärkningar



Exempel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathBlockCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)