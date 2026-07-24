---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) Methode

Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Element, das in der Sammlung zu finden ist. |

### Rückgabewert

Der Index von *item*, falls er in der Sammlung gefunden wird; sonst -1.
## Anmerkungen



Beispiel: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathElementCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)