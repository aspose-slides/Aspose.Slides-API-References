---
title: categories property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories 屬性
取得主要類別（或同時取得主要與次要類別，如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 false）。唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)。


### 備註

如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 false，則 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性 返回 None，且此 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性 中的資料同時用於主要與次要系列。
如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) 屬性 為 true，則 [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 屬性 中的資料用於次要系列，而此 [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) 屬性 中的資料用於主要系列。

### 定義:
```python
@property
def categories(self):
    ...
```


### 另見
* 類別 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)