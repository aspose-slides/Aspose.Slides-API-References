---
title: Reorder()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormcollectie.
type: docs
weight: 339
url: /nl/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) methode


Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormcollectie.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde doelindex waar de vorm geplaatst zal worden. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) die verplaatst moet worden binnen de collectie. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) methode


Verplaatst de opgegeven vormen binnen de vormcollectie, en plaatst ze beginnend bij de opgegeven index.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde doelindex waar de eerste opgegeven vorm wordt geplaatst; daaropvolgende vormen volgen in de opgegeven volgorde. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Een of meer [IShape](../../ishape/) instanties die binnen de collectie verplaatst moeten worden. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)