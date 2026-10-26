---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny cell i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method


Lägg till en ny cell i samlingen.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Ny cell att lägga till. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) method


Skapar [IChartDataCell](../../ichartdatacell/) från angivet värde och lägger till det i samlingen.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |
## Anmärkningar



Denna metod lägger till ett kalkylblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [IChartDataWorkbook](../../ichartdataworkbook/) för att lägga till eller redigera [Cell](../../../aspose.slides/cell/)-värden, se till att du inte använder detta kalkylblad. Maximalt antal värden som läggs till med denna metod får inte överstiga 16711680



## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [IChartCellCollection](../)
* Klass [Object](../../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)