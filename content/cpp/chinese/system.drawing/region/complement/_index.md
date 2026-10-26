---
title: Complement()
second_title: Aspose.Slides C++ API 参考
description: 将当前对象表示的区域替换为由指定矩形定义的、未与此区域相交的部分。
type: docs
weight: 131
url: /zh/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) 方法

将当前对象表示的区域替换为由指定的矩形定义的、未与此区域相交的部分。

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定义要补集的区域的矩形 |

## Region::Complement(const Rectangle\&) 方法

将当前对象表示的区域替换为由指定的矩形定义的、未与此区域相交的部分。

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定义要补集的区域的矩形 |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法

将当前对象表示的区域替换为由指定路径定义的、未与此区域相交的部分。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定义要补集的区域的路径 |

## Region::Complement(const SharedPtr\<Region\>\&) 方法

将当前对象表示的区域替换为未与此区域相交的、由指定区域定义的部分。

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 要补集的区域 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Region](../)
* 类 [Rectangle](../../rectangle/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)