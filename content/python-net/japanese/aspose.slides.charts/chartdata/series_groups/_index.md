---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups プロパティ
シリーズのグループを取得します。
            読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection).

### 備考

1) 各シリーズグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは、CombinableSeriesTypesGroup 列挙体で定義および説明されています。
            また、各シリーズグループは、主軸または副軸のいずれかにプロットされるシリーズを含みます（同一グループ内で両方のケースはありません）。
            したがって、シリーズのグルーピングの原則は、上記のタイプグループと主軸/副軸のプロットタイプによるグルーピングです。

2) シリーズグループは、グループ内の各シリーズに共通するいくつかのシリーズプロパティを含みます（「series group properties」）。
            ChartSeriesGroup クラスの「Series group properties」は読み書き可能です。
            「Series group properties」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。

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