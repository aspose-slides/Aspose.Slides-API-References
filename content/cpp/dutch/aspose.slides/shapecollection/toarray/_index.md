---
title: ToArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt en retourneert een array die alle vormen bevat.
type: docs
weight: 326
url: /nl/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() methode


Maakt en retourneert een array die alle vormen bevat.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Retourwaarde

Een array van [IShape](../../ishape/) objecten.

## ShapeCollection::ToArray(int32_t, int32_t) methode


Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
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
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)