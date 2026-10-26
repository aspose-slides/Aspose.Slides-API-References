---
title: RectangleF class
second_title: Aspose.Slides for Python via .NET API 参考
description: 存储一组四个浮点数，表示矩形的位置和大小。
type: docs
url: /zh/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF 类

存储一组四个浮点数，表示矩形的位置和大小。兼容 .NET `System.Drawing.RectangleF`。

**继承:**[`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/zh/aspose.slides/rectangle)

RectangleF 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/zh/aspose.slides/rectanglef/__init__/#float-float-float-float) | 使用指定的位置和大小创建一个矩形。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`x`](/slides/python-net/zh/aspose.slides/rectanglef/x/) | 获取此矩形左上角的 x 坐标。<br/>            只读 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/rectanglef/y/) | 获取此矩形左上角的 y 坐标。<br/>            只读 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/rectanglef/width/) | 获取此矩形的宽度。<br/>            只读 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/rectanglef/height/) | 获取此矩形的高度。<br/>            只读 **float**. |
| [`left`](/slides/python-net/zh/aspose.slides/rectanglef/left/) | 获取此矩形左边缘的 x 坐标。等于 `x`。<br/>            只读 **float**. |
| [`top`](/slides/python-net/zh/aspose.slides/rectanglef/top/) | 获取此矩形上边缘的 y 坐标。等于 `y`。<br/>            只读 **float**. |
| [`right`](/slides/python-net/zh/aspose.slides/rectanglef/right/) | 获取此矩形的 x 坐标，该坐标为 `x` 与宽度 `width` 的和。<br/>            只读 **float**. |
| [`bottom`](/slides/python-net/zh/aspose.slides/rectanglef/bottom/) | 获取此矩形的 y 坐标，该坐标为 `y` 与高度 `height` 的和。<br/>            只读 **float**. |
| [`is_empty`](/slides/python-net/zh/aspose.slides/rectanglef/is_empty/) | 指定此矩形的所有数值属性是否均为零。<br/>            只读 **bool**. |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/zh/aspose.slides/rectanglef/contains/#float-float) | 确定指定的点是否位于此矩形内。 |
| [`contains(self, point)`](/slides/python-net/zh/aspose.slides/rectanglef/contains/#pointf) | 确定指定的点是否位于此矩形内。 |
| [`contains(self, rect)`](/slides/python-net/zh/aspose.slides/rectanglef/contains/#rectanglef) | 确定由 `rect` 表示的矩形区域是否完全位于此矩形内。 |

### 备注

矩形可以使用 `==` 根据其位置和大小进行比较，并且可以用作字典键或集合成员。

### 另见
* 类 [`Rectangle`](/slides/python-net/zh/aspose.slides/rectangle)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)