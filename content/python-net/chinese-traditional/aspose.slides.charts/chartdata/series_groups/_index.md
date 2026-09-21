---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups 屬性
Gets the groups of series.
            唯讀 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection).


### 備註

1) 每個 series 群組包含具有可組合類型的 series。可組合 series 類型的群組使用 CombinableSeriesTypesGroup enum 定義和說明。每個 series 群組亦包含在主座標軸或次座標軸上繪製的 series（同一群組中不會同時在兩種座標軸上繪製）。因此，series 分組的原則是依上述類型群組以及主/次座標軸繪製類型進行分組。

2) series 群組包含一些對於群組中每個 series 皆通用的 series 屬性（"series group properties"）。"Series group properties" 在 ChartSeriesGroup 類別中為讀寫。每個 "series group properties" 皆可在 ChartSeries 類別中擁有唯讀投影。

### 定義：
```python
@property
def series_groups(self):
    ...
```


### 另請參閱
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 類別 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)