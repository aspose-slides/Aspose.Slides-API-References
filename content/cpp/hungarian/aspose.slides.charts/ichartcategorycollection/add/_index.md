---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: Ha a kategória létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre az IChartDataCell-ből, és hozzáadja a gyűjteményhez.
type: docs
weight: 53
url: /hu/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metódus


Ha a kategória létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre a [IChartDataCell](../../ichartdatacell/) alapján, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) használva diagramkategória létrehozásához. |

### Visszatérési érték

Hozzáadott vagy létező kategória.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metódus


Új [IChartCategory](../../ichartcategory/)-t hoz létre az értékből, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Az érték. |

### Visszatérési érték

Hozzáadott [IChartCategory](../../ichartcategory/).
## Megjegyzés



Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda teszi az összes értéket. Ha a [IChartDataWorkbook](../../ichartdataworkbook/)-t használja cellaértékek hozzáadására vagy szerkesztésére, győződjön meg róla, hogy ezt a munkalapot nem használja. Ezzel a metódussal hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.



## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCategory](../../ichartcategory/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [IChartCategoryCollection](../)
* Osztály [Object](../../../system/object/)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)