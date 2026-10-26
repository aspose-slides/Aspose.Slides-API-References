---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny cell i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metod


Lägg till en ny cell i samlingen.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Ny cell att lägga till. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) metod


Skapar [ChartDataCell](../../chartdatacell/) från angivet värde och lägger till den i samlingen.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |
## Anmärkningar

Denna metod lägger till ett arbetsblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [ChartDataWorkbook](../../chartdataworkbook/) för att lägga till eller redigera [Cell](../../../aspose.slides/cell/)-värden, se till att du inte använder detta arbetsblad Det maximala antalet värden som läggs till med denna metod får inte överstiga 16711680

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [ChartCellCollection](../)
* Klass [Object](../../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)