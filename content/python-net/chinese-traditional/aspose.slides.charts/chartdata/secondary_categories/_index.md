---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories 屬性
如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 true，則取得次要類別。
            唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)。


### 備註

如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 false，則此 [`ChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/secondary_categories) 屬性返回 None，且 [`ChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/categories) 屬性中的資料同時用於主要和次要系列。
            如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/use_secondary_categories) 屬性為 true，則此 [`ChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/secondary_categories) 屬性中的資料用於次要系列，[`ChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/categories) 屬性中的資料用於主要系列。

### 定義：
```python
@property
def secondary_categories(self):
    ...
```


### 另請參閱
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 類別 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)