---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API Referansı
description: "Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. ChartType'ı Column veya Bar alt tiplerinden biri olan seriler için geçerlidir (bkz. ChartTypeCharacterizer::IsChartTypeColumn(ChartType) ve ChartTypeCharacterizer::IsChartTypeBar(ChartType) yöntemi)."
type: docs
weight: 261
url: /tr/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) yöntemi

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. [Column](../../../aspose.slides/column/) veya Bar alt tiplerinden birine sahip olan seriler için geçerlidir (bkz. [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) ve [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) yöntemi).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Veri noktası Değeri |

### Dönüş Değeri

Yeni veri noktası.

## ChartDataPointCollection::AddDataPointForBarSeries(double) yöntemi

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. [Column](../../../aspose.slides/column/) veya Bar alt tiplerinden birine sahip olan seriler için geçerlidir (bkz. [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) ve [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) yöntemi).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Veri noktası Değeri |

### Dönüş Değeri

Yeni veri noktası.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [ChartDataPointCollection](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)