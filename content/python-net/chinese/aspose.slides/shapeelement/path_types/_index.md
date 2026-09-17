---
title: path_types property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types 属性
获取一个字节值数组，用于指定元素路径中每个点的类型。 

**0**  表示该点是图形的起始点。

**1**  表示该点是直线的两个端点之一。

**3**  表示该点是三次贝塞尔样条的端点或控制点。

**7**  掩码除三个低位之外的所有位，这三个低位指示点的类型。

**16**  指定相应的段为虚线。

**32**  指定该点是标记点。

**128**  指定该点是闭合子路径（图形）中的最后一点。

**129**  表示该数据点既是线段端点也是闭合子路径的最后一点。

### 定义:
```python
@property
def path_types(self):
    ...
```

### 另见
* 类 [`ShapeElement`](/slides/python-net/zh/aspose.slides/shapeelement)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)