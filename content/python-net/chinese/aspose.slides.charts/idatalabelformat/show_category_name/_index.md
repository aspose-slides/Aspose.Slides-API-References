---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name 属性
表示指定图表的数据标签类别名称的显示行为。
            True 表示在图表上显示数据标签的类别名称。False 表示隐藏。
            读/写 **bool**。


### 备注

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。
            使用该值设置此属性时，也会将该值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性。
            (例如 "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 会导致所有 DataLabels[i].ShowCategoryName 等于 val)。

### 定义：
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### 另见
* 类 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)