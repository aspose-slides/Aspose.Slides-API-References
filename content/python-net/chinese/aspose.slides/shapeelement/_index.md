---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapeelement/
---
## ShapeElement 类

表示具有相同轮廓和填充属性的形状的一部分。

ShapeElement 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/zh/aspose.slides/shapeelement/parent_shape/) | 返回创建该元素的 Shape_PPT。<br/>            只读 [`Shape`](/slides/python-net/zh/aspose.slides/shape). |
| [`path_points`](/slides/python-net/zh/aspose.slides/shapeelement/path_points/) | 获取定义元素路径几何形状的点数组。 |
| [`path_types`](/slides/python-net/zh/aspose.slides/shapeelement/path_types/) | 获取一个字节值数组，用于指定路径中每个点的类型。 <br/>            <br/>**0** 表示该点是图形的起始点。<br/><br/><br/>**1** 表示该点是线段的两个端点之一。<br/><br/><br/>**3** 表示该点是三次贝塞尔曲线的端点或控制点。<br/><br/><br/>**7** 掩盖除最低三位之外的所有位，这三位指示点的类型。<br/><br/><br/>**16** 指定相应的段是虚线。<br/><br/><br/>**32** 指定该点是标记。<br/><br/><br/>**128** 指定该点是闭合子路径（图形）的最后一点。<br/><br/><br/>**129** 表示既是线段端点又是闭合子路径最后一点的数据点。 |
| [`fill_source`](/slides/python-net/zh/aspose.slides/shapeelement/fill_source/) | 返回关于如何填充元素的信息。<br/>            只读 [`ShapeElementFillSource`](/slides/python-net/zh/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/zh/aspose.slides/shapeelement/stroke_source/) | 返回关于如何描边元素的信息。<br/>            只读 [`ShapeElementStrokeSource`](/slides/python-net/zh/aspose.slides/shapeelementstrokesource). |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)