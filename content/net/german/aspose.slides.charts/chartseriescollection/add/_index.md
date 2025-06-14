---
title: Add
second_title: Aspose.Slides für .NET API-Referenz
description: Erstellt neue Diagrammserien und fügt sie der Sammlung hinzu.
type: docs
weight: 50
url: /de/aspose.slides.charts/chartseriescollection/add/
---

## Add(ChartType) {#add}

Erstellt neue Diagrammserien und fügt sie der Sammlung hinzu.

```csharp
public IChartSeries Add(ChartType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | ChartType | Typ der Serie |

### Rückgabewert

Neue Diagrammserie.

### Siehe auch

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* namespace [Aspose.Slides.Charts](../../chartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## Add(IChartDataCell, ChartType) {#add_2}

Erstellt neue Diagrammserien aus [`ChartDataCell`](../../chartdatacell) und fügt sie der Sammlung hinzu.

```csharp
public IChartSeries Add(IChartDataCell cellWithSeriesName, ChartType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellWithSeriesName | IChartDataCell | Zelle, die den Seriennamen enthält. |
| type | ChartType | Typ, der den Typ der Serie festlegt |

### Rückgabewert

Hinzugefügte Diagrammserie oder Serie, die sich bereits in der Sammlung befindet.

### Anmerkungen

Wenn die Diagrammserie, die aus derselben Zelle erstellt wurde, bereits in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.

### Siehe auch

* interface [IChartSeries](../../ichartseries)
* interface [IChartDataCell](../../ichartdatacell)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* namespace [Aspose.Slides.Charts](../../chartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## Add(IChartCellCollection, ChartType) {#add_1}

Erstellt neue Diagrammserien aus [`ChartCellCollection`](../../chartcellcollection) und fügt sie der Sammlung hinzu.

```csharp
public IChartSeries Add(IChartCellCollection cellsWithSeriesName, ChartType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellsWithSeriesName | IChartCellCollection | Zellen, die den Seriennamen enthalten. |
| type | ChartType | Typ, der den Typ der Serie festlegt |

### Rückgabewert

Hinzugefügte Diagrammserie oder Serie, die sich bereits in der Sammlung befindet.

### Anmerkungen

Wenn die Diagrammserie, die aus derselben Zelle erstellt wurde, bereits in der Sammlung vorhanden ist, fügt die Methode nichts hinzu und gibt ihren Index zurück.

### Siehe auch

* interface [IChartSeries](../../ichartseries)
* interface [IChartCellCollection](../../ichartcellcollection)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* namespace [Aspose.Slides.Charts](../../chartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## Add(string, ChartType) {#add_3}

Erstellt neue Diagrammserien aus einem Wert und fügt sie der Sammlung hinzu.

```csharp
public IChartSeries Add(string name, ChartType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Serienname. |
| type | ChartType | Typ, der den Typ der Serie festlegt |

### Rückgabewert

Hinzugefügte Diagrammserie.

### Siehe auch

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* namespace [Aspose.Slides.Charts](../../chartseriescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->