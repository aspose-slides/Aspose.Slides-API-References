---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories 属性
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) property is true.
            只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection).

### 备注

如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性为 false，则此 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 
            属性返回 None，[`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中的数据用于主系列和 
            次级系列。
            如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性为 true，则数据在 
            此 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 属性用于次级系列，且数据 
            在 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中用于主系列。

### 定义:
```python
@property
def secondary_categories(self):
    ...
```

### 另请参见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)