---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der Column- oder Bar-Untertypen ist (siehe auch ChartTypeCharacterizer.IsChartTypeColumn(ChartType) und ChartTypeCharacterizer.IsChartTypeBar(ChartType) Methode).
type: docs
weight: 196
url: /de/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der [Column](../../../aspose.slides/column/) oder Bar-Unterelemente ist (siehe auch die Methode [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) und [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wert des Datenpunkts |

### Rückgabewert

Neuer Datenpunkt.

## IChartDataPointCollection::AddDataPointForBarSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Serien, deren chartType einer der [Column](../../../aspose.slides/column/) oder Bar-Unterelemente ist (siehe auch [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) und [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Wert des Datenpunkts |

### Rückgabewert

Neuer Datenpunkt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)