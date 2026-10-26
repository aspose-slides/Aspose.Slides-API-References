---
title: Exclude()
second_title: Aspose.Slides for C++ API 参考
description: 用当前对象表示的区域替换为从中排除指定矩形定义的区域后的结果。
type: docs
weight: 92
url: /zh/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) method


将当前对象表示的区域替换为从中排除指定矩形定义的区域后的结果。

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定义要排除的区域的矩形 |

## Region::Exclude(const Rectangle\&) method


将当前对象表示的区域替换为从中排除指定矩形定义的区域后的结果。

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定义要排除的区域的矩形 |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


将当前对象表示的区域替换为从中排除指定路径定义的区域后的结果。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定义要排除的区域的路径 |

## Region::Exclude(const SharedPtr\<Region\>\&) method


将当前对象表示的区域替换为从中排除指定区域后的结果。

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 要排除的区域 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Region](../)
* 类 [Rectangle](../../rectangle/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)