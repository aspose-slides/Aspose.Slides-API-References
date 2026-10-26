---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API 参考
description: 存储一组四个整数，表示矩形的位置和大小。
type: docs
url: /zh/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle 类

存储四个整数，表示矩形的位置和大小。兼容 .NET `System.Drawing.Rectangle`。

Rectangle 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/zh/aspose.slides/rectangle/__init__/#int-int-int-int) | 创建一个具有指定位置和大小的矩形。浮点值将被截断为整数。 |

## 属性

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/zh/aspose.slides/rectangle/x/) | 获取此矩形左上角的 x 坐标。<br/>            只读 **int**。 |
| [`y`](/slides/python-net/zh/aspose.slides/rectangle/y/) | 获取此矩形左上角的 y 坐标。<br/>            只读 **int**。 |
| [`width`](/slides/python-net/zh/aspose.slides/rectangle/width/) | 获取此矩形的宽度。<br/>            只读 **int**。 |
| [`height`](/slides/python-net/zh/aspose.slides/rectangle/height/) | 获取此矩形的高度。<br/>            只读 **int**。 |
| [`left`](/slides/python-net/zh/aspose.slides/rectangle/left/) | 获取此矩形左边缘的 x 坐标。等于 `x`。<br/>            只读 **int**。 |
| [`top`](/slides/python-net/zh/aspose.slides/rectangle/top/) | 获取此矩形上边缘的 y 坐标。等于 `y`。<br/>            只读 **int**。 |
| [`right`](/slides/python-net/zh/aspose.slides/rectangle/right/) | 获取此矩形的 x 坐标加上宽度的和。<br/>            只读 **int**。 |
| [`bottom`](/slides/python-net/zh/aspose.slides/rectangle/bottom/) | 获取此矩形的 y 坐标加上高度的和。<br/>            只读 **int**。 |
| [`is_empty`](/slides/python-net/zh/aspose.slides/rectangle/is_empty/) | 指定此矩形的所有数值属性是否全部为零。<br/>            只读 **bool**。 |

## 方法

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/zh/aspose.slides/rectangle/contains/#int-int) | 确定指定点是否位于此矩形内部。 |
| [`contains(self, point)`](/slides/python-net/zh/aspose.slides/rectangle/contains/#point) | 确定指定点是否位于此矩形内部。 |
| [`contains(self, rect)`](/slides/python-net/zh/aspose.slides/rectangle/contains/#rectangle) | 确定由 `rect` 表示的矩形区域是否完全包含在此矩形内。 |


### 备注

矩形通过其位置和大小使用 `==` 进行比较，可用作字典键或集合成员。


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)