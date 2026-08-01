---
title: Reorder()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling.
type: docs
weight: 300
url: /nl/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) methode

Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde doelindex waar de vorm wordt geplaatst. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te verplaatsen binnen de verzameling. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) methode

Verplaatst de opgegeven vormen binnen de vormverzameling en plaatst ze beginnend op de opgegeven index.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde doelindex waar de eerste opgegeven vorm wordt geplaatst; daaropvolgende vormen volgen in de opgegeven volgorde. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Een of meer [IShape](../../ishape/) exemplaren om te verplaatsen binnen de verzameling. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)