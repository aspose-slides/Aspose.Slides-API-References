---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用されます（ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照）。
type: docs
weight: 222
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries/
---
## IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用されます（[ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値 |

### 戻り値

新しいデータポイント。

## IChartDataPointCollection::AddDataPointForPieSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用されます（[ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(double value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | データポイントの値 |

### 戻り値

新しいデータポイント。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)