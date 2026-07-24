---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. ChartType'ı Column veya Bar alt türlerinden biri olan seriler için uygulanabilir (ayrıca ChartTypeCharacterizer.IsChartTypeColumn(ChartType) ve ChartTypeCharacterizer.IsChartTypeBar(ChartType) metoduna bakınız).
type: docs
weight: 196
url: /tr/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) metodu

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. [Column](../../../aspose.slides/column/) veya Bar alt türlerinden biri olan chartType sahip seriler için uygulanabilir (ayrıca [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) ve [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoduna bakınız).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Veri noktası Değeri |

### Dönüş Değeri

Yeni veri noktası.

## IChartDataPointCollection::AddDataPointForBarSeries(double) metodu

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. [Column](../../../aspose.slides/column/) veya Bar alt türlerinden biri olan chartType sahip seriler için uygulanabilir (ayrıca [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) ve [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) metoduna bakınız).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Veri noktası Değeri |

### Dönüş Değeri

Yeni veri noktası.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [IChartDataPointCollection](../)
* İsim Uzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)