---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides C++ API referenciája
description: Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható azoknál a sorozatoknál, ahol a chartType a Stock altípusok egyike (lásd még a ChartTypeCharacterizer.IsChartTypeStock(ChartType) metódust).
type: docs
weight: 144
url: /hu/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) metódus

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Stock altípusok egyike (lásd még [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metódus).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value. |

### Visszatérési érték

Új adatpont.

## IChartDataPointCollection::AddDataPointForStockSeries(double) metódus

Létrehozza az új adatpontot, és a gyűjtemény végéhez adja hozzá. Alkalmazható olyan sorozatokra, amelyek chartType értéke a Stock altípusok egyike (lásd még [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) metódus).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | Data point Value. |

### Visszatérési érték

Új adatpont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataPoint](../../ichartdatapoint/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [IChartDataPointCollection](../)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)