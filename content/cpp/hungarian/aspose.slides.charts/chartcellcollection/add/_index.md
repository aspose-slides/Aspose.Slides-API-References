---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Új cellát ad a gyűjteményhez.
type: docs
weight: 53
url: /hu/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metódus

Új cellát ad a gyűjteményhez.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Az új cella, amelyet hozzáad. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) metódus

Létrehozza a(z) [ChartDataCell](../../chartdatacell/) a megadott értékből, és hozzáadja a gyűjteményhez.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Az érték. |

## Megjegyzések

Ez a metódus egy AUTO_DATA nevű munkalapot ad hozzá, és oda helyezi az összes értéket. Ha a(z) [ChartDataWorkbook](../../chartdataworkbook/)-t használja [Cell](../../../aspose.slides/cell/) értékek hozzáadásához vagy szerkesztéséhez, ügyeljen arra, hogy ne használja ezt a munkalapot. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [ChartCellCollection](../)
* Osztály [Object](../../../system/object/)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)