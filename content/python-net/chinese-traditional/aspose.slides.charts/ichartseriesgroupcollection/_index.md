---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection 類別

表示可組合系列的群組集合。

IChartSeriesGroupCollection 類型公開以下成員：

透過索引取得系列群組。

## 索引子

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### 備註

1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組以 `CombinableSeriesTypesGroup` 列舉定義並說明。  
   同時，每個系列群組包含的系列會繪製在主要軸或次要軸上（同一群組中不會同時存在兩者）。  
   因此，系列分組的原則是依上述的類型群組以及主要/次要繪製類型進行分組。

2) 系列群組包含一些對於群組內每個系列共通的系列屬性（「系列群組屬性」）。`ChartSeriesGroup` 類別中的「系列群組屬性」為可讀寫。  
   每個「系列群組屬性」在 `ChartSeries` 類別中可以有唯讀的投影。

### 另見
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)