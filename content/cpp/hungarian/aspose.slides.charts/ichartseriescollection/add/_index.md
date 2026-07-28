---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.
type: docs
weight: 14
url: /hu/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metódus

Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Sorozat típusa |

### Visszatérési érték

Új diagram sorozat.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metódus

Új diagram sorozatot hoz létre a [IChartDataCell](../../ichartdatacell/) alapján, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) amely tartalmazza a sorozat nevét. |
| type | [ChartType](../../charttype/) | Sorozat típusa |

### Visszatérési érték

A hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

## Megjegyzések

Ha a diagram sorozat ugyanabból a cellából származik, amely már a gyűjteményben van, akkor a metódus nem ad hozzá semmit, és visszaadja annak indexét.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metódus

Új diagram sorozatot hoz létre a [IChartCellCollection](../../ichartcellcollection/) alapján, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cellák, amelyek tartalmazzák a sorozat nevét. |
| type | [ChartType](../../charttype/) | Sorozat típusa |

### Visszatérési érték

A hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

## Megjegyzések

Ha a diagram sorozat ugyanabból a cellából származik, amely már a gyűjteményben van, akkor a metódus nem ad hozzá semmit, és visszaadja annak indexét.

## IChartSeriesCollection::Add(System::String, ChartType) metódus

Új diagram sorozatot hoz létre az érték alapján, és hozzáadja a gyűjteményhez.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Sorozat neve. |
| type | [ChartType](../../charttype/) | Sorozat típusa |

### Visszatérési érték

A hozzáadott diagram sorozat.

## Lásd még

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)