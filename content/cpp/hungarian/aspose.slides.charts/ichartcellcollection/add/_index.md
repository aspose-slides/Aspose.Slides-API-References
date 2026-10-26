---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: Új cellát ad a gyűjteményhez.
type: docs
weight: 53
url: /hu/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metódus


Új cellát ad a gyűjteményhez.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Új cella a hozzáadáshoz. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metódus


Létrehozza a(z) [IChartDataCell](../../ichartdatacell/) a megadott értékből, és hozzáadja a gyűjteményhez.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Az érték. |
## Megjegyzés



Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda helyezi az összes értéket. Ha a(z) [IChartDataWorkbook](../../ichartdataworkbook/)-t használja [Cell](../../../aspose.slides/cell/) értékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ezt a munkalapot ne használja. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.



## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [IChartCellCollection](../)
* Osztály [Object](../../../system/object/)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)