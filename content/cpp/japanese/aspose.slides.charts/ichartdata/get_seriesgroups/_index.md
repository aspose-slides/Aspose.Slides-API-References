---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズのグループを取得します。読み取り専用 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ja/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() メソッド


シリーズのグループを取得します。読み取り専用 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)。

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## 備考


1) 各シリーズのグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは CombinableSeriesTypesGroup enum で定義および記述されています。また、各シリーズのグループは、主軸または副軸のいずれかにプロットされるシリーズを含みます（同一グループ内で両方にプロットされることはありません）。したがって、シリーズのグルーピングの原則は、上記のタイプ グループと主軸/副軸のプロットタイプによるグルーピングです。

2) シリーズのグループは、グループ内の各シリーズに共通するいくつかの「シリーズ グループ プロパティ」を含みます。[ChartSeriesGroup](../../chartseriesgroup/) クラスの「シリーズ グループ プロパティ」は読み書き可能です。「シリーズ グループ プロパティ」の各項目は、[ChartSeries](../../chartseries/) クラスで読み取り専用のプロジェクションを持つことができます。 
## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)