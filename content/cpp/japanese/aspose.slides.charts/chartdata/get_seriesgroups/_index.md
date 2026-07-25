---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズのグループを取得します。読み取り専用 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ja/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() メソッド

シリーズのグループを取得します。読み取り専用 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## 備考

1) 各シリーズグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは、CombinableSeriesTypesGroup 列挙型で定義および記述されています。また、各シリーズグループは、一次軸または二次軸のいずれかにプロットされるシリーズを含みます（1つのグループで両方のケースはありません）。したがって、シリーズのグルーピングの原則は、前述のタイプグループと一次/二次プロットタイプによるグルーピングです。

2) シリーズのグループには、グループ内の各シリーズに共通するいくつかのシリーズプロパティ（「series group properties」）が含まれます。「Series group properties」は [ChartSeriesGroup](../../chartseriesgroup/) クラスで読み書き可能です。「series group properties」の各項目は、[ChartSeries](../../chartseries/) クラスで読み取り専用の投影を持つことができます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)