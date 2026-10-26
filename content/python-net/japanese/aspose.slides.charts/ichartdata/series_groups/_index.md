---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups プロパティ
Gets the groups of series.
読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection).

### 備考

1) Each group of series contains series with combinable types. Groups of 
combinable series types defined and described with CombinableSeriesTypesGroup 
enum.
Also each group of series contains series witch is plotted whether 
on primary axes or on secondary axes (not both cases in one group).
So, principle of series grouping is a grouping by type groups mentioned 
above and by primary/secondary plotting type.

2) Group of series contains some series properies whitch is common for 
each series in group ("series group properties").
"Series group properties" in ChartSeriesGroup class is read/write.
Each of "series group properties" can have a read-only projection in ChartSeries class.

### 定義:
```python
@property
def series_groups(self):
    ...
```

### 参照
* クラス [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata)
* クラス [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)