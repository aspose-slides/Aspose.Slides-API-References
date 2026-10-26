---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的資料點並將其加入集合的末端。適用於 chartType 為 Surface 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。
type: docs
weight: 261
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries/
---
## IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 傳回值

新的資料點。

## IChartDataPointCollection::AddDataPointForSurfaceSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(double value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 傳回值

新的資料點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)