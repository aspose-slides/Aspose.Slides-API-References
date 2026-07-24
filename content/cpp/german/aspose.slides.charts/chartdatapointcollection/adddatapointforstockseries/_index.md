---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch ChartTypeCharacterizer::IsChartTypeStock(ChartType) Methode)."
type: docs
weight: 209
url: /de/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) Methode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Datenpunktwert. |

### Rückgabewert

Neuer Datenpunkt.

## ChartDataPointCollection::AddDataPointForStockSeries(double) Methode

Erstellt den neuen Datenpunkt und fügt ihn am Ende der Sammlung hinzu. Gültig für Serien, deren chartType einer der Stock-Untertypen ist (siehe auch [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) Methode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Datenpunktwert. |

### Rückgabewert

Neuer Datenpunkt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)