---
title: use_cell property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartcategory/use_cell/
weight: 50
---
## use_cell 属性
如果为 true，则 AsCell 属性为实际的。换句话说，worksheet 用于存储 category（此情况支持多层级 category）。
如果为 false，则 AsLiteral 属性为实际的。换句话说，worksheet **不**用于存储 category（且此情况不支持多层级 category）。
只读 **bool**。

### 备注

为了更改此属性的值（针对集合中的所有 categories），请将新值设置到 ChartCategoryCollection.UseCells 属性。

### 定义:
```python
@property
def use_cell(self):
    ...
```

### 另请参见
* 类 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)