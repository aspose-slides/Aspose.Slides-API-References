---
title: AddDataPointForAreaSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: "新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer::IsChartTypeArea(ChartType) メソッドも参照）。"
type: docs
weight: 274
url: /ja/aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries/
---
## ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr\<IChartDataCell\>) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area サブタイプのいずれかであるシリーズに適用可能です（[ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) メソッドを参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr<IChartDataCell> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値 |

### 戻り値

新しいデータポイント。

## ChartDataPointCollection::AddDataPointForAreaSeries(double) メソッド

新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area サブタイプのいずれかであるシリーズに適用可能です（[ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) メソッドを参照）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(double value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | データポイントの値 |

### 戻り値

新しいデータポイント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)