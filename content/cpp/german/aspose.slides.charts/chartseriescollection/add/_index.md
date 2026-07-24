---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt neue Diagrammserien und fügt sie der Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) Methode

Erstellt eine neue Diagrammreihe und fügt sie der Sammlung hinzu.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ der Reihe |

### Rückgabewert

Neue Diagrammreihe.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) Methode

Erstellt eine neue Diagrammreihe aus [ChartDataCell](../../chartdatacell/) und fügt sie der Sammlung hinzu.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) die den Seriennamen enthält. |
| type | [ChartType](../../charttype/) | Legt den Typ der Reihe fest. |

### Rückgabewert

Hinzugefügte Diagrammreihe oder bereits in der Sammlung vorhandene Reihe.

## Anmerkungen

Wenn die Diagrammreihe aus derselben Zelle, die bereits in der Sammlung ist, erstellt wird, fügt die Methode nichts hinzu und gibt ihren Index zurück.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) Methode

Erstellt eine neue Diagrammreihe aus [ChartCellCollection](../../chartcellcollection/) und fügt sie der Sammlung hinzu.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Zellen, die den Seriennamen enthalten. |
| type | [ChartType](../../charttype/) | Legt den Typ der Reihe fest. |

### Rückgabewert

Hinzugefügte Diagrammreihe oder bereits in der Sammlung vorhandene Reihe.

## Anmerkungen

Wenn die Diagrammreihe aus derselben Zelle, die bereits in der Sammlung ist, erstellt wird, fügt die Methode nichts hinzu und gibt ihren Index zurück.

## ChartSeriesCollection::Add(System::String, ChartType) Methode

Erstellt eine neue Diagrammreihe aus dem Wert und fügt sie der Sammlung hinzu.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Serienname. |
| type | [ChartType](../../charttype/) | Legt den Typ der Reihe fest. |

### Rückgabewert

Hinzugefügte Diagrammreihe.

## Siehe auch

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [ChartSeriesCollection](../)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCellCollection](../../ichartcellcollection/)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)