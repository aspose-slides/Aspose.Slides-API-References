---
title: Add()
second_title: Aspose.Slides C++ API Referenciája
description: Ha a kategória létezik a gyűjteményben, visszaadja. Egyébként új diagramkategóriát hoz létre az IChartDataCell alapján, és hozzáadja a gyűjteményhez.
type: docs
weight: 92
url: /hu/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metódus

Ha a kategória már létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre a [IChartDataCell](../../ichartdatacell/) alapján, és hozzáadja a gyűjteményhez.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) used to create chart category. |

### Visszatérési érték

A hozzáadott vagy már meglévő kategória.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metódus

Új [ChartCategory](../../chartcategory/) létrehozása az értékből, és hozzáadása a gyűjteményhez.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Visszatérési érték

Hozzáadott [IChartCategory](../../ichartcategory/).

## Megjegyzések

Ez a metódus egy AUTO_DATA nevű munkalapot ad hozzá, és minden értéket oda helyez. Ha a [ChartDataWorkbook](../../chartdataworkbook/)-t használja cellaértékek hozzáadásához vagy szerkesztéséhez, ügyeljen arra, hogy ne használja ezt a munkalapot. A metódus által hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

## Kapcsolódó

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCategory](../../ichartcategory/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [ChartCategoryCollection](../)
* Osztály [Object](../../../system/object/)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)