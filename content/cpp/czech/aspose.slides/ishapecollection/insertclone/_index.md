---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii určeného tvaru a vloží ji do kolekce tvarů na určeném indexu.
type: docs
weight: 508
url: /cs/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

Vytvoří kopii určeného tvaru a vloží ji do kolekce tvarů na určeném indexu.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ke klonování. |
| x | **float** | Souřadnice x rámce klonovaného tvaru, v bodech. |
| y | **float** | Souřadnice y rámce klonovaného tvaru, v bodech. |
| width | **float** | Šířka rámce klonovaného tvaru, v bodech. |
| height | **float** | Výška rámce klonovaného tvaru, v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

Vytvoří kopii určeného tvaru a vloží ji do kolekce tvarů na určeném indexu. Nový tvar si zachová šířku a výšku *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ke klonování. |
| x | **float** | Souřadnice x rámce klonovaného tvaru, v bodech. |
| y | **float** | Souřadnice y rámce klonovaného tvaru, v bodech. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

Vytvoří kopii určeného tvaru a vloží ji do kolekce tvarů na určeném indexu. Klonovaný tvar si zachová původní polohu a velikost.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit klonovaný tvar. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ke klonování. |

### Návratová hodnota

Nově vytvořený [IShape](../../ishape/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShape](../../ishape/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)