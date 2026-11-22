---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups 屬性
取得系列的群組。
            唯讀 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection).

### 備註

1) 每個系列組包含具有可組合類型的系列。可組合系列類型的組別以 CombinableSeriesTypesGroup 列舉定義並描述。  
此外，每個系列組包含的系列會繪製在主要坐標軸上或次要坐標軸上（不會在同一組中同時出現在兩者）。  
因此，系列分組的原則是依上述類型組以及主要/次要繪製類型進行分組。

2) 系列組包含一些對該組內每個系列共通的系列屬性（「series group properties」）。  
ChartSeriesGroup 類別中的「Series group properties」為讀寫。  
每個「Series group properties」在 ChartSeries 類別中可以有唯讀的投影。

### 定義：
```python
@property
def series_groups(self):
    ...
```

### 參見
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 類別 [`IChartSeriesGroupCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)