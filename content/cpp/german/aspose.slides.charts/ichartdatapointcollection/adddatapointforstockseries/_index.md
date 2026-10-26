---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Reihen, deren chartType einer der Stock-Subtypen ist (siehe auch ChartTypeCharacterizer.IsChartTypeStock(ChartType) Methode).
type: docs
weight: 144
url: /de/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Reihen, deren chartType einer der Stock-Untertypen ist (siehe auch [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Wert des Datenpunkts. |

### Rückgabewert

Neuer Datenpunkt.

## IChartDataPointCollection::AddDataPointForStockSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Anwendbar für Reihen, deren chartType einer der Stock-Untertypen ist (siehe auch [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) Methode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
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
* Klasse [IChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)