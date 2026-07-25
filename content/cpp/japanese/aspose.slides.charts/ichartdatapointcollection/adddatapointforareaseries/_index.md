---
title: AddDataPointForAreaSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Area のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照）。
type: docs
weight: 209
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries/
---
## IChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Area のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値 |

### 戻り値

新しいデータポイント。

## IChartDataPointCollection::AddDataPointForAreaSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Area のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForAreaSeries(double value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | データポイントの値 |

### 戻り値

新しいデータポイント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)