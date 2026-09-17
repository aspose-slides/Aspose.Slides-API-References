---
title: use_secondary_categories property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/use_secondary_categories/
weight: 150
---
## use_secondary_categories 属性
If false then [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 属性 return None and data 
            在 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中同时用于主系列和次系列。
            If true then data in [`ChartData.secondary_categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/secondary_categories) 属性 is used for secondary series and data 
            在 [`ChartData.categories`](/slides/python-net/zh/aspose.slides.charts/chartdata/categories) 属性中用于主系列。
            读/写 **bool**.

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
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)