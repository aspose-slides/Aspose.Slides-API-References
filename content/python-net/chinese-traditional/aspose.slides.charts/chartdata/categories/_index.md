---
title: categories property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/categories/
weight: 70
---

## categories 屬性
取得主要類別（如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 false，則同時取得主要與次要類別）。
唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)。

### 備註

如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 false，則 [`ChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/secondary_categories) 屬性返回 None，且此 [`ChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/categories) 屬性中的資料同時用於主要與次要序列。
如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 true，則 [`ChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/secondary_categories) 屬性中的資料用於次要序列，而此 [`ChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/categories) 屬性中的資料用於主要序列。

### 定義:
```python
@property
def categories(self):
    ...
```

### 另見
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 類別 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)