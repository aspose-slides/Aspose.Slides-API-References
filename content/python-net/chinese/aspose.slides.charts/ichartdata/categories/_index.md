---
title: categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories 属性
获取主分类（或如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则同时获取主分类和次分类）。
只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection).

### 备注

如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性返回 None，且此 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据同时用于主系列和次系列。
如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 true，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性中的数据用于次系列，而此 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据用于主系列。

### 定义:
```python
@property
def categories(self):
    ...
```

### 另见
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)