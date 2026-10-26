---
title: categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/categories/
weight: 70
---
## 类别属性
获取主要类别（如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性 为 false，则获取主要和次要类别）。
只读 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)。

### 备注

如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性 为 false 则 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 属性 返回 None，且此 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性 中的数据用于主要和次要序列。
如果 [`ChartData.use_secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/use_secondary_categories) 属性 为 true 则 [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 属性 中的数据用于次要序列，且此 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性 中的数据用于主要序列。

### 定义：
```python
@property
def categories(self):
    ...
```

### 另请参阅
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 类 [`IChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)