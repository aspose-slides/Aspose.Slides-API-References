---
title: categories property
second_title: Aspose.Slides 的 Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories 属性
获取主要类别（如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则获取主要和次要类别）。
            只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection).

### 备注

如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories)
            属性返回 None，且此 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据同时用于主要
            和次要序列。
            如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 true，则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories)
            属性中的数据用于次要序列，而此 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据用于主要序列。

### 定义：
```python
@property
def categories(self):
    ...
```

### 另请参见
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)