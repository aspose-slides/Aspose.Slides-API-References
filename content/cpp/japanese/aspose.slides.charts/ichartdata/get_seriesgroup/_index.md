---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 222
url: /ja/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) メソッド


```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) メソッド


指定されたインデックスの系列グループを返します。

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## 備考


1) 系列の各グループは、組み合わせ可能なタイプの系列を含みます。組み合わせ可能な系列タイプのグループは CombinableSeriesTypesGroup enum で定義および記述されています。また、各系列グループは、主軸上にプロットされる系列または副軸上にプロットされる系列を含みます（同一グループ内で両方が混在することはありません）。したがって、系列のグループ化の原則は、上記のタイプグループと主/副軸のプロットタイプによるグループ化です。 2) 系列のグループは、グループ内の各系列に共通するいくつかの系列プロパティ（\"シリーズ グループ プロパティ\"）を含みます。[ChartSeriesGroup](../../chartseriesgroup/) クラスの \"シリーズ グループ プロパティ\" は読み書き可能です。各 \"シリーズ グループ プロパティ\" は [ChartSeries](../../chartseries/) クラスで読み取り専用の投影を持つことができます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeriesGroup](../../ichartseriesgroup/)
* クラス [IChartSeries](../../ichartseries/)
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)