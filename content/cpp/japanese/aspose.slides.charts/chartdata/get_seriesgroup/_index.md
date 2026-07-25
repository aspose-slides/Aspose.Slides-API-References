---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 222
url: /ja/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) method




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) method


指定されたインデックスのシリーズグループを返します。

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## 備考


1) 各シリーズグループは、組み合わせ可能な型を持つシリーズを含みます。組み合わせ可能なシリーズ型のグループは CombinableSeriesTypesGroup enum で定義および説明されています。また、各シリーズグループは、一次軸上にプロットされるシリーズまたは二次軸上にプロットされるシリーズを含みます（同一グループ内で両方が混在することはありません）。したがって、シリーズのグループ化の原則は、前述の型グループと一次/二次プロットタイプによるグループ化です。 2) シリーズグループには、グループ内のすべてのシリーズに共通するいくつかのシリーズプロパティ（\"series group properties\"）が含まれます。[ChartSeriesGroup](../../chartseriesgroup/) クラスの\"series group properties\"は 読み取り/書き込み です。\"series group properties\" の各項目は [ChartSeries](../../chartseries/) クラスで 読み取り専用 のプロジェクションを持つことができます。 
## 参考

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeriesGroup](../../ichartseriesgroup/)
* クラス [IChartSeries](../../ichartseries/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)