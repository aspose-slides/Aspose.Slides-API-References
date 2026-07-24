---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, bei denen chartType einer der Pie-Untertpyen ist (siehe auch ChartTypeCharacterizer::IsChartTypePie(ChartType) Methode)."
type: docs
weight: 287
url: /de/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, bei denen chartType einer der Pie-Untertpyen ist (siehe auch [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) Methode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wert des Datenpunkts |
| value | **double** | Wert des Datenpunkts |

### Rückgabewert

Neuer Datenpunkt.

## ChartDataPointCollection::AddDataPointForPieSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, bei denen chartType einer der Pie-Untertpyen ist (siehe auch [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) Methode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Wert des Datenpunkts |

### Rückgabewert

Neuer Datenpunkt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)