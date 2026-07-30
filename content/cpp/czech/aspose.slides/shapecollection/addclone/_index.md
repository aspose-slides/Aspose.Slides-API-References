---
title: AddClone()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.
type: docs
weight: 547
url: /cs/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metoda


Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Tvar, který se má klonovat. |
| x | **float** | Souřadnice x rámce nového tvaru v bodech. |
| y | **float** | Souřadnice y rámce nového tvaru v bodech. |
| width | **float** | Šířka rámce nového tvaru v bodech. |
| height | **float** | Výška rámce nového tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metoda


Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar si zachová šířku a výšku *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Tvar, který se má klonovat. |
| x | **float** | Souřadnice x rámce nového tvaru v bodech. |
| y | **float** | Souřadnice y rámce nového tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) metoda


Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Klonovaný tvar si zachová původní pozici a velikost.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/), který se má klonovat. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)