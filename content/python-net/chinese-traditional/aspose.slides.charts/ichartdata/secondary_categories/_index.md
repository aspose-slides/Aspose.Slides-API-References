---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories 屬性
如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 true，則取得次要類別。
唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection).

### 備註

如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 false，則此 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性 會回傳 None，且 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性 中的資料同時用於主要和次要系列。
如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 true，則 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性 中的資料 用於次要系列，而 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性 中的資料 用於主要系列。

### 定義:
```python
@property
def secondary_categories(self):
    ...
```

### 另見
* 類別 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)