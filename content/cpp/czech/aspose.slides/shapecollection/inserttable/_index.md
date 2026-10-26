---
title: InsertTable()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaném indexu.
type: docs
weight: 482
url: /cs/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metoda

Vytvoří novou table a vloží ji do ShapeCollection na určeném indexu.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index, do kterého se má vložit table. |
| x | **float** | Souřadnice x table, v bodech. |
| y | **float** | Souřadnice y table, v bodech. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole double hodnot představujících šířky sloupců table, v bodech. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole double hodnot představujících výšky řádků table, v bodech. |

### Návratová hodnota

Nově vytvořený [ITable](../../itable/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ITable](../../itable/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)