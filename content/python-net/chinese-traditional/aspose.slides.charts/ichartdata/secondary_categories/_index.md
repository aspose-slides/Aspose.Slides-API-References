---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories 屬性
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) property is true.
            唯讀 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection).


### Remarks

If [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) property is false then this [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) 
            property return None and data in [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/use_secondary_categories) property is true then data in 
            this [`IChartData.secondary_categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/secondary_categories) property is used for secondary series and data 
            in [`IChartData.categories`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata/categories) property is used for primary series.

### 定義：
```python
@property
def secondary_categories(self):
    ...
```


### See Also
* 類別 [`IChartCategoryCollection`](/slides/python-net/zh-hant/aspose.slides.charts/ichartcategorycollection)
* 類別 [`IChartData`](/slides/python-net/zh-hant/aspose.slides.charts/ichartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)