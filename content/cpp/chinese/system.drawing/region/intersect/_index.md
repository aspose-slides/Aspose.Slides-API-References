---
title: Intersect()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象表示的区域替换为此区域与由指定矩形定义的区域的交集结果。
type: docs
weight: 79
url: /zh/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) 方法


将当前对象表示的区域替换为此区域与由指定矩形定义的区域的交集结果。

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 一个矩形，用于定义与此区域相交的区域 |

## Region::Intersect(const Rectangle\&) 方法


将当前对象表示的区域替换为此区域与由指定矩形定义的区域的交集结果。

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 一个矩形，用于定义与此区域相交的区域 |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法


将当前对象表示的区域替换为此区域与由指定路径定义的区域的交集结果。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 一条路径，用于定义与此区域相交的区域 |

## Region::Intersect(const SharedPtr\<Region\>\&) 方法


将当前对象表示的区域替换为此区域与指定区域的交集结果。

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 一个区域，用于与此区域相交 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)