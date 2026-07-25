---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用されます（ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドを参照）。
type: docs
weight: 183
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries/
---
## IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用されます（[ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) メソッドを参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値 |

### 戻り値

新しいデータポイント。

## IChartDataPointCollection::AddDataPointForRadarSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用されます（[ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) メソッドを参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(double value)=0
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
* ライブラリ [Aspose.Slides](../../../)