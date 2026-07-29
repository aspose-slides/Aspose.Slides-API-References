---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Om kategori finns i samlingen, returneras den. Annars skapas en ny diagramkategori från IChartDataCell och läggs till i samlingen.
type: docs
weight: 92
url: /sv/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metod


Om kategori finns i samlingen, returneras den. Annars skapas en ny diagramkategori från [IChartDataCell](../../ichartdatacell/) och läggs till i samlingen.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) används för att skapa diagramkategori. |

### Returvärde

Tillagd eller befintlig kategori.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metod


Skapar en ny [ChartCategory](../../chartcategory/) från värdet och lägger till den i samlingen.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |

### Returvärde

Tillagd [IChartCategory](../../ichartcategory/).
## Anmärkningar



Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [ChartDataWorkbook](../../chartdataworkbook/) för att lägga till eller redigera cellvärden, se till att du inte använder detta kalkylblad. Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680



## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartCategory](../../ichartcategory/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [ChartCategoryCollection](../)
* Klass [Object](../../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)