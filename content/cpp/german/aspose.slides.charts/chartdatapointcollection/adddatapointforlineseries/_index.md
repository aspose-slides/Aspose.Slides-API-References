---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untertypen ist (siehe auch ChartTypeCharacterizer::IsChartTypeLine(ChartType) method)."
type: docs
weight: 222
url: /de/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untertypen ist (siehe auch [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) method).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wert des Datenpunkts. |

### Rückgabewert

Neuer Datenpunkt.

## ChartDataPointCollection::AddDataPointForLineSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gilt für Serien, deren chartType einer der Line-Untertypen ist (siehe auch [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) method).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Wert des Datenpunkts. |

### Rückgabewert

Neuer Datenpunkt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)