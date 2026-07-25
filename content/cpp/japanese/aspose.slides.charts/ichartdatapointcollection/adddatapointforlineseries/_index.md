---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照）。
type: docs
weight: 157
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値。 |

### 戻り値

新しいデータポイント。

## IChartDataPointCollection::AddDataPointForLineSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（[ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | データポイントの値。 |

### 戻り値

新しいデータポイント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)