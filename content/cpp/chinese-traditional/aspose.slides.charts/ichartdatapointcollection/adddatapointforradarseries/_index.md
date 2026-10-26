---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的資料點並將其加入集合的末端。適用於 chartType 為 Radar 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。
type: docs
weight: 183
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries/
---
## IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Radar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 傳回值

新的資料點。

## IChartDataPointCollection::AddDataPointForRadarSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Radar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(double value)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 傳回值

新的資料點。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)