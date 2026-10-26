---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories 属性
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性 is true.
Read-only [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection).

### 备注

如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 false，则此 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 
            属性返回 None，且 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据用于主 
            和次要系列。
如果 [`IChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/use_secondary_categories) 属性为 true，则数据在 
            此 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性用于次要系列，且数据 
            在 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中用于主系列。

### 定义:
```python
@property
def secondary_categories(self):
    ...
```

### 另请参见
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)