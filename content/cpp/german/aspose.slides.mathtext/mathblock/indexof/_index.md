---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.
type: docs
weight: 144
url: /de/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) Methode


Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Element, das in der Sammlung gefunden werden soll. |

### Rückgabewert

Der Index von *item*, falls er in der Sammlung gefunden wird; andernfalls -1.
## Bemerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)