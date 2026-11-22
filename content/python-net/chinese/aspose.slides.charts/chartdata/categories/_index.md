---
title: categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/categories/
weight: 80
---
## 类别属性
获取主要类别（如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性为 false，则同时获取主要和次要类别）。
            只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)。

### 备注

如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性为 false，则 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 
            属性返回 None 并且此 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中的数据同时用于主要 
            和次要系列。
            如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性为 true，则 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 
            属性用于次要系列，并且此 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中的数据用于 
            主要系列。

### 定义:
```python
@property
def categories(self):
    ...
```

### 另见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)