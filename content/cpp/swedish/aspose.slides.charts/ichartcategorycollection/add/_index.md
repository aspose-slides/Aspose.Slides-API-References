---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Om kategorin finns i samlingen, returneras den. Annars skapar den en ny diagramkategori från IChartDataCell och lägger till den i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metod


Om kategorin finns i samlingen, returneras den. Annars skapas en ny diagramkategori från [IChartDataCell](../../ichartdatacell/) och läggs till i samlingen.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) used to create chart category. |

### Returvärde

Tillagd eller befintlig kategori.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metod


Skapar ny [IChartCategory](../../ichartcategory/) från värdet och lägger den till i samlingen.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Returvärde

Tillagd [IChartCategory](../../ichartcategory/).
## Anmärkningar



Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [IChartDataWorkbook](../../ichartdataworkbook/) för att lägga till eller redigera cellvärden, se till att du inte använder detta kalkylblad. Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680



## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)