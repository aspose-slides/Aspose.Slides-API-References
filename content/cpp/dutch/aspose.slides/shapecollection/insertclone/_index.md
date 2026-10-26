---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven vorm en voegt deze in de shape collection in op de opgegeven index.
type: docs
weight: 560
url: /nl/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) methode

Maakt een kopie van de opgegeven vorm en voegt deze in de ShapeCollection in op de opgegeven index.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de geklonede vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de geklonede vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de geklonede vorm\\u2019s, in punten. |
| width | **float** | De breedte van het frame van de geklonede vorm\\u2019s, in punten. |
| height | **float** | De hoogte van het frame van de geklonede vorm\\u2019s, in punten. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) methode

Maakt een kopie van de opgegeven vorm en voegt deze in de ShapeCollection in op de opgegeven index. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de geklonede vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de geklonede vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de geklonede vorm\\u2019s, in punten. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) methode

Maakt een kopie van de opgegeven vorm en voegt deze in de ShapeCollection in op de opgegeven index. De geklonede vorm behoudt de oorspronkelijke positie en grootte.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de geklonede vorm moet worden ingevoegd. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)