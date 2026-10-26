---
title: overlap property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## 重疊屬性
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            此屬性不僅屬於此序列，還屬於父序列群組的所有序列。 
            它是父序列群組中相應屬性的投影，因此此屬性為唯讀。 
            若要更改值，請使用 ParentSeriesGroup.Overlap 可讀寫 屬性。 
            唯讀 **int**。

### 備註
Overlap 指定條形圖和柱狀圖之間的重疊或間距程度，以其寬度的百分比表示:
            - -100%: 最大間距（條形圖完全分開）。 
            - 0%: 條形圖並排放置，沒有重疊或間距。 
            - 100%: 最大重疊（條形圖彼此完全重疊）。 
            這是屬性 ParentSeriesGroup.Overlap 的投影。

### 定義：
```python
@property
def overlap(self):
    ...
```

### 另請參閱
* 類別 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)