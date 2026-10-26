---
title: AddTable()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.
type: docs
weight: 430
url: /cs/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metoda

Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | x-souřadnice tabulky v bodech. |
| y | **float** | y-souřadnice tabulky v bodech. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole double představujících šířky sloupců tabulky v bodech. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Pole double představujících výšky řádků tabulky v bodech. |

### Návratová hodnota

Nově vytvořený [ITable](../../itable/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ITable](../../itable/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)