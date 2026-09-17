---
title: data_source_type property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/doublechartvalue/data_source_type/
weight: 70
---
## data_source_type 属性
指定后代中实际使用的是 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性。换句话说，它指定 Data 属性的值的类型。读/写 [`DataSourceType`](/slides/python-net/zh/aspose.slides.charts/datasourcetype)。


### 备注

对于 ChartDataPointCollection 中的点，此属性是只读的。 在这种情况下，要更改此属性的值，您可以使用 ChartDataPointCollection.DataSourceTypeFor<...> 属性之一。

### 定义:
```python
@property
def data_source_type(self):
    ...

@data_source_type.setter
def data_source_type(self, value):
    ...
```


### 另请参阅
* 枚举 [`DataSourceType`](/slides/python-net/zh/aspose.slides.charts/datasourcetype)
* 类 [`DoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/doublechartvalue)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)