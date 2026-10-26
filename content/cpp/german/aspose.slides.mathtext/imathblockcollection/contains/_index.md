---
title: Contains()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die Sammlung einen bestimmten Wert enthält.
type: docs
weight: 66
url: /de/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) Methode

Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Das Objekt, das in der Sammlung gefunden werden soll. |

### Rückgabewert

true, wenn *item* in der Sammlung gefunden wird; andernfalls false.
## Bemerkungen


Beispiel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)