---
title: AddClone()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.
type: docs
weight: 495
url: /cs/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metoda

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Tvar, který se má klonovat. |
| x | **float** | X-souřadnice rámce klonovaného tvaru v bodech. |
| y | **float** | Y-souřadnice rámce klonovaného tvaru v bodech. |
| width | **float** | Šířka rámce klonovaného tvaru v bodech. |
| height | **float** | Výška rámce klonovaného tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metoda

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar zachová šířku a výšku *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k naklonování. |
| x | **float** | X-souřadnice rámce klonovaného tvaru v bodech. |
| y | **float** | Y-souřadnice rámce klonovaného tvaru v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metoda

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Klonovaný tvar zachová původní pozici a velikost.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k naklonování. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IShape](../../ishape/)
* třída [IShapeCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)