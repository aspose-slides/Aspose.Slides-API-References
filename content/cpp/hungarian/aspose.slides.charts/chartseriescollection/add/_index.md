---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.
type: docs
weight: 53
url: /hu/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) módszer


Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | A sorozat típusa |

### Return Value

Új diagram sorozat.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) módszer


Új diagram sorozatot hoz létre a(z) [ChartDataCell](../../chartdatacell/) alapján, és hozzáadja a gyűjteményhez.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) amely tartalmazza a sorozat nevét. |
| type | [ChartType](../../charttype/) | A sorozat típusát beállító típus |

### Return Value

Hozzáadott diagram sorozat, vagy a már a gyűjteményben lévő sorozat.

## Remarks


Ha a diagram sorozat ugyanabból a cellából jön, amely már a gyűjteményben van, a módszer semmit sem ad hozzá, és visszaadja az indexét.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) módszer


Új diagram sorozatot hoz létre a(z) [ChartCellCollection](../../chartcellcollection/) alapján, és hozzáadja a gyűjteményhez.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cellák, amelyek sorozatnevet tartalmaznak. |
| type | [ChartType](../../charttype/) | A sorozat típusát beállító típus |

### Return Value

Hozzáadott diagram sorozat, vagy a már a gyűjteményben lévő sorozat.

## Remarks


Ha a diagram sorozat ugyanabból a cellából jön, amely már a gyűjteményben van, a módszer semmit sem ad hozzá, és visszaadja az indexét.



## ChartSeriesCollection::Add(System::String, ChartType) módszer


Új diagram sorozatot hoz létre az érték alapján, és hozzáadja a gyűjteményhez.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Sorozat neve. |
| type | [ChartType](../../charttype/) | A sorozat típusát beállító típus |

### Return Value

Hozzáadott diagram sorozat.



## Lásd még

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)