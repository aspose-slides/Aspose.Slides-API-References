---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.
type: docs
weight: 560
url: /cs/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metoda

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k klonování. |
| x | **float** | x-souřadnice rámečku klonovaného tvaru v bodech. |
| y | **float** | y-souřadnice rámečku klonovaného tvaru v bodech. |
| width | **float** | Šířka rámečku klonovaného tvaru v bodech. |
| height | **float** | Výška rámečku klonovaného tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metoda

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. Nový tvar zachová šířku a výšku *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k klonování. |
| x | **float** | x-souřadnice rámečku klonovaného tvaru v bodech. |
| y | **float** | y-souřadnice rámečku klonovaného tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metoda

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. Klonovaný tvar zachová pozici a velikost originálu.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k klonování. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)