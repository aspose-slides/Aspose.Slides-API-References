---
title: Contains()
second_title: Aspose.Slides C++ API 参考
description: 确定指定的点是否位于当前对象表示的矩形内部。
type: docs
weight: 248
url: /zh/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const 方法

确定指定的点是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要检查的点的 X 坐标 |
| y | int | 要检查的点的 Y 坐标 |

### 返回值

True 如果指定的点位于当前对象表示的矩形内部，否则 - false

## Rectangle::Contains(const Point\&) const 方法

确定指定的点是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 要检查的点 |

### 返回值

True 如果指定的点位于当前对象表示的矩形内部，否则 - false

## Rectangle::Contains(const Rectangle\&) const 方法

确定指定的矩形是否位于当前对象表示的矩形内部。

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 要检查的矩形 |

### 返回值

True 如果指定的矩形位于当前对象表示的矩形内部，否则 - false

## 另请参见

* 类 [Rectangle](../)
* 类 [Point](../../point/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)