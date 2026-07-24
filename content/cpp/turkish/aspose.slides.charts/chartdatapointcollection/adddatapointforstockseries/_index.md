---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API Referansı
description: "Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Serinin chartType değeri Stock alt tiplerinden biri olduğunda uygulanır (bkz. ChartTypeCharacterizer::IsChartTypeStock(ChartType) yöntemi)."
type: docs
weight: 209
url: /tr/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) yöntemi


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Seri için chartType değeri Stock alt tiplerinden biri olduğunda uygulanır (bkz. [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) yöntemi).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Veri noktası Değeri. |

### Dönüş Değeri

Yeni veri noktası.

## ChartDataPointCollection::AddDataPointForStockSeries(double) yöntemi


Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Seri için chartType değeri Stock alt tiplerinden biri olduğunda uygulanır (bkz. [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) yöntemi).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | **double** | Veri noktası Değeri. |

### Dönüş Değeri

Yeni veri noktası.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)