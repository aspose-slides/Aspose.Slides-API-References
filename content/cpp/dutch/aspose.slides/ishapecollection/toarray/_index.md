---
title: ToArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een array aan en retourneert deze die alle vormen bevat.
type: docs
weight: 287
url: /nl/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() methode


Creëert en retourneert een array die alle vormen bevat.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Retourwaarde

Een array van [IShape](../../ishape/) objecten.

## IShapeCollection::ToArray(int32_t, int32_t) methode


Creëert en retourneert een array die alle vormen in het opgegeven bereik bevat.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **int32_t** | De index van de eerste vorm die moet worden geretourneerd. |
| count | **int32_t** | Het aantal vormen dat moet worden geretourneerd. |

### Retourwaarde

Een array van [IShape](../../ishape/) objecten.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)