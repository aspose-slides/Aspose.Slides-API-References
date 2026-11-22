---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups 屬性
Gets the groups of series.
            唯讀 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection).


### 備註

1) Each group of series contains series with combinable types. Groups of 
            combinable series types defined and described with CombinableSeriesTypesGroup 
            enum.
            Also each group of series contains series witch is plotted whether 
            on primary axes or on secondary axes (not both cases in one group).
            So, principle of series grouping is a grouping by type groups mentioned 
            above and by primary/secondary plotting type.
            
            2) Group of series contains some series properies whitch is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup 類別 is 可讀寫.
            Each of "series group properties" can have a 唯讀 projection in ChartSeries 類別.

### 定義：
```python
@property
def series_groups(self):
    ...
```


### 參見
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 類別 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)