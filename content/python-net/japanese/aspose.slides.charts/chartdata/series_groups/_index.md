---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups プロパティ
Gets the groups of series.
            読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection).

### 備考

1) 各シリーズのグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプは CombinableSeriesTypesGroup enum で定義および説明されています。また、各シリーズのグループは、主軸または副軸のいずれかにプロットされるシリーズを含みます（同一グループ内で両方はありません）。したがって、シリーズのグループ化の原則は、上記のタイプグループと主軸/副軸のプロットタイプによるグループ化です。

2) シリーズのグループは、グループ内の各シリーズに共通するいくつかのシリーズプロパティ（「シリーズ グループ プロパティ」）を含みます。ChartSeriesGroup クラスの「シリーズ グループ プロパティ」は読み書き可能です。「シリーズ グループ プロパティ」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。

### 定義:
```python
@property
def series_groups(self):
    ...
```

### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* クラス [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)