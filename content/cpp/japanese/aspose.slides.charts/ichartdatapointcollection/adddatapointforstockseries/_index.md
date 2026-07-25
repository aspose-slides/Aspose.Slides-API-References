---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照）。
type: docs
weight: 144
url: /ja/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) メソッド


新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかである系列に適用できます（[ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | データポイントの値。 |

### 戻り値

新しいデータ ポイント。

## IChartDataPointCollection::AddDataPointForStockSeries(double) メソッド


新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかである系列に適用できます（[ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) メソッドも参照）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | データポイントの値。 |

### 戻り値

新しいデータ ポイント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)