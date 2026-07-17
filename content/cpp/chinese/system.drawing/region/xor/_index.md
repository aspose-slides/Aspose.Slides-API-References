---
title: Xor()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象代表的区域替换为该区域与由指定矩形定义的区域的非交叉部分。
type: docs
weight: 144
url: /zh/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) 方法

将当前对象代表的区域替换为该区域与由指定矩形定义的区域的非交叉部分。

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定义要与当前对象代表的区域进行异或的矩形 |

## Region::Xor(const Rectangle\&) 方法

将当前对象代表的区域替换为该区域与由指定矩形定义的区域的非交叉部分。

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定义要与当前对象代表的区域进行异或的矩形 |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 方法

将当前对象代表的区域替换为该区域与由指定路径定义的区域的非交叉部分。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定义与当前对象代表的区域进行异或的路径 |

## Region::Xor(const SharedPtr\<Region\>\&) 方法

将当前对象代表的区域替换为该区域与指定区域的非交叉部分。

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 用于与当前对象代表的区域进行异或的区域 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Region](../)
* 类 [Rectangle](../../rectangle/)
* 类 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空间 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)