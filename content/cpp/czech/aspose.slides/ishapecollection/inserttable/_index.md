---
title: InsertTable()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou tabulku a vloží ji do kolekce tvarů na určený index.
type: docs
weight: 443
url: /cs/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Vytvoří novou tabulku a vloží ji do kolekce tvarů na určený index.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index založený na nule, na který se má tabulka vložit. |
| x | **float** | X-souřadnice tabulky v bodech. |
| y | **float** | Y-souřadnice tabulky v bodech. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole typu double představující šířky sloupců tabulky v bodech. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole typu double představující výšky řádků tabulky v bodech. |

### Návratová hodnota

Nově vytvořený [ITable](../../itable/).

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [ITable](../../itable/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)