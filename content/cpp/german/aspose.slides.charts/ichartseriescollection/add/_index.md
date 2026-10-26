---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt neue Diagrammreihen und fügt sie der Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) Methode

Erstellt eine neue Diagrammreihe und fügt sie der Sammlung hinzu.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ der Reihe |

### Rückgabewert

Neue Diagrammreihe.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) Methode

Erstellt eine neue Diagrammreihe aus [IChartDataCell](../../ichartdatacell/) und fügt sie der Sammlung hinzu.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) die den Namen der Reihe enthält. |
| type | [ChartType](../../charttype/) | Typ, der den Typ der Reihe festlegt. |

### Rückgabewert

Hinzugefügte Diagrammreihe oder eine bereits in der Sammlung vorhandene Reihe.

## Hinweise

Wenn die Diagrammreihe bereits aus derselben Zelle in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) Methode

Erstellt eine neue Diagrammreihe aus [IChartCellCollection](../../ichartcellcollection/) und fügt sie der Sammlung hinzu.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Zellen, die den Namen der Reihe enthalten. |
| type | [ChartType](../../charttype/) | Typ, der den Typ der Reihe festlegt. |

### Rückgabewert

Hinzugefügte Diagrammreihe oder eine bereits in der Sammlung vorhandene Reihe.

## Hinweise

Wenn die Diagrammreihe bereits aus derselben Zelle in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.



## IChartSeriesCollection::Add(System::String, ChartType) Methode

Erstellt eine neue Diagrammreihe aus dem Wert und fügt sie der Sammlung hinzu.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Name der Reihe. |
| type | [ChartType](../../charttype/) | Typ, der den Typ der Reihe festlegt. |

### Rückgabewert

Hinzugefügte Diagrammreihe.



## Siehe auch

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)