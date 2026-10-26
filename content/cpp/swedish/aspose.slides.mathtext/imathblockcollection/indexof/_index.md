---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer indexet för ett specifikt IMathBlock i samlingen.
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) metod

Bestämmer indexet för ett specifikt [IMathBlock](../../imathblock/) i samlingen.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objektet att hitta i samlingen. |

## Returvärde

Indexet för *item* om den hittas i samlingen; annars -1.

## Anmärkningar



Exempel:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathBlockCollection](../)
* Namnområde [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)