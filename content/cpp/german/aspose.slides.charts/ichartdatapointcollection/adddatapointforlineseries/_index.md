---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untersorten ist (siehe auch ChartTypeCharacterizer.IsChartTypeLine(ChartType) Methode).
type: docs
weight: 157
url: /de/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untersorten ist (siehe auch [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wert des Datenpunkts. |

### Rückgabewert

Neuer Datenpunkt.

## IChartDataPointCollection::AddDataPointForLineSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untersorten ist (siehe auch [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Wert des Datenpunkts. |

### Rückgabewert

Neuer Datenpunkt.

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)