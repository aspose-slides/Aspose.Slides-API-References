---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index.
type: docs
weight: 508
url: /nl/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) methode

Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm\\u2019s, in punten. |
| width | **float** | De breedte van het frame van de gekloonde vorm\\u2019s, in punten. |
| height | **float** | De hoogte van het frame van de gekloonde vorm\\u2019s, in punten. |

### Retourwaarde

Het nieuw aangemaakte [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) methode

Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm\\u2019s, in punten. |

### Retourwaarde

Het nieuw aangemaakte [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) methode

Maakt een kopie van de opgegeven vorm en voegt deze toe aan de vormverzameling op de opgegeven index. Het gekloonde object behoudt de positie en afmetingen van het origineel\\u2019s.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |

### Retourwaarde

Het nieuw aangemaakte [IShape](../../ishape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)