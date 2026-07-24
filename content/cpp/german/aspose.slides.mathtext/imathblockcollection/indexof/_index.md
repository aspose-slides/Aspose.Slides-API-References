---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index eines bestimmten IMathBlock in der Sammlung.
type: docs
weight: 79
url: /de/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) Methode

Ermittelt den Index eines bestimmten [IMathBlock](../../imathblock/) in der Sammlung.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Das Element *item*, das in der Sammlung gesucht werden soll. |

### Rückgabewert

Der Index von *item*, falls in der Sammlung gefunden, andernfalls -1.

## Anmerkungen



Beispiel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)