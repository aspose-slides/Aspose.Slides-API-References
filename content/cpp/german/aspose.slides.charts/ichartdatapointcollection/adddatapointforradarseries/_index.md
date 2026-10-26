---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, bei denen chartType einer der Radar-Untersorten ist (siehe auch die Methode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).
type: docs
weight: 183
url: /de/aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries/
---
## IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) Methode

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datenpunktwert |

### Rückgabewert

Neuer Datenpunkt.

## IChartDataPointCollection::AddDataPointForRadarSeries(double) Methode

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(double value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Datenpunktwert |

### Rückgabewert

Neuer Datenpunkt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)