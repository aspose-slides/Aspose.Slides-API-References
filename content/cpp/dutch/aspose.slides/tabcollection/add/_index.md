---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een Tab toe aan de collectie.
type: docs
weight: 53
url: /nl/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) methode

Voegt een [Tab](../../tab/) toe aan de collectie.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Retourwaarde

Toegevoegd tabblad.

## TabCollection::Add(System::SharedPtr\<ITab\>) methode

Voegt een [Tab](../../tab/) toe aan de collectie.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Het [Tab](../../tab/) object dat aan het einde van de collectie moet worden toegevoegd. |

### Retourwaarde

De index waarop het tabblad werd toegevoegd.

## Zie ook

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)