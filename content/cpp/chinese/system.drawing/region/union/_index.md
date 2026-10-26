---
title: Union()
second_title: Aspose.Slides C++ API 参考
description: 用当前对象表示的区域替换为此区域与由指定矩形定义的区域的并集结果。
type: docs
weight: 53
url: /zh/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) 方法

用当前对象表示的区域替换为此区域与由指定矩形定义的区域的并集结果。

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 用于定义一个与此区域合并的矩形 |

## Region::Union(const Rectangle\&) 方法

用当前对象表示的区域替换为此区域与由指定矩形定义的区域的并集结果。

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 用于定义一个与此区域合并的矩形 |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法

用当前对象表示的区域替换为此区域与由指定路径定义的区域的并集结果。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 用于定义一个与此区域合并的路径 |

## Region::Union(const SharedPtr\<Region\>\&) 方法

用当前对象表示的区域替换为此区域与指定区域的并集结果。

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 用于定义一个与此区域合并的区域 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Region](../)
* 类 [Rectangle](../../rectangle/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)