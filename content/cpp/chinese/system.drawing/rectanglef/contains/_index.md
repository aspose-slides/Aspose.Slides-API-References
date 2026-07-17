---
title: Contains()
second_title: Aspose.Slides C++ API 参考
description: 确定指定的点是否位于当前对象表示的矩形内部。
type: docs
weight: 248
url: /zh/system.drawing/rectanglef/contains/
---
## RectangleF::Contains(float, float) 方法


确定指定的点是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::RectangleF::Contains(float x, float y)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 要检查的点的 X 坐标 |
| y | **float** | 要检查的点的 Y 坐标 |

### 返回值

如果指定的点位于当前对象表示的矩形内部，则返回 True；否则返回 false

## RectangleF::Contains(const PointF\&) 方法


确定指定的点是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::RectangleF::Contains(const PointF &point)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 要检查的点 |

### 返回值

如果指定的点位于当前对象表示的矩形内部，则返回 True；否则返回 false

## RectangleF::Contains(const RectangleF\&) 方法


确定指定的矩形是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::RectangleF::Contains(const RectangleF &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 要检查的矩形 |

### 返回值

如果指定的矩形位于当前对象表示的矩形内部，则返回 True；否则返回 false

## 另见

* 类 [RectangleF](../)
* 类 [PointF](../../pointf/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)