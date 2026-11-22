---
title: use_secondary_categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/use_secondary_categories/
weight: 160
---
## use_secondary_categories 属性
如果 false 则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性返回 None 并且 [`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据同时用于主系列和次系列。
如果 true 则 [`IChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/secondary_categories) 属性中的数据用于次系列，[`IChartData.categories`](/slides/python-net/zh/aspose.slides.charts/ichartdata/categories) 属性中的数据用于主系列。
读/写 **bool**。

### 定义:
```python
@property
def use_secondary_categories(self):
    ...

@use_secondary_categories.setter
def use_secondary_categories(self, value):
    ...
```

### 另见
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)