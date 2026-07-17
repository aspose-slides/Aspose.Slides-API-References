---
title: IsVisible()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定的点是否位于当前对象所表示的区域内。
type: docs
weight: 196
url: /zh/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const 方法

确定指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 要检查的点 |

## Region::IsVisible(const PointF\&) const 方法

确定指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 要检查的点 |

## Region::IsVisible(const Rectangle\&) 方法

确定指定的矩形的任何部分是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 要检查的矩形 |

## Region::IsVisible(const RectangleF\&) 方法

确定指定的矩形的任何部分是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 要检查的矩形 |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const 方法

确定使用指定的图形时，指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 要检查的点 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 图形上下文 |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const 方法

确定使用指定的图形时，指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 要检查的点 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 图形上下文 |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) 方法

确定使用指定的图形时，指定的矩形的任何部分是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 要检查的矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 图形上下文 |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) 方法

确定使用指定的图形时，指定的矩形的任何部分是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 要检查的矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 图形上下文 |

## Region::IsVisible(float, float) const 方法

确定指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 要检查的点的 X 坐标 |
| y | **float** | 要检查的点的 Y 坐标 |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const 方法

确定使用指定的图形时，指定的点是否位于当前对象所表示的区域内。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 要检查的点的 X 坐标 |
| y | **float** | 要检查的点的 Y 坐标 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 图形上下文 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Point](../../point/)
* 类 [Region](../)
* 类 [PointF](../../pointf/)
* 类 [Rectangle](../../rectangle/)
* 类 [RectangleF](../../rectanglef/)
* 类 [Graphics](../../graphics/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)