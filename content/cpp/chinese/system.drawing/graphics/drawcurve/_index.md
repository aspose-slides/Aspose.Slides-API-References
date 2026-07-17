---
title: DrawCurve()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的笔绘制样条。
type: docs
weight: 794
url: /zh/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) 方法

使用指定的笔绘制样条。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制样条的 pen |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 用于确定样条的点 |
| tension | **float** | 指定样条张力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) 方法

使用指定的笔绘制样条。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制样条的 pen |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 用于确定样条的点 |
| tension | **float** | 指定样条张力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) 方法

使用指定的笔绘制样条。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制样条的 pen |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 用于确定样条的点 |
| offset | **int32_t** | **points** 数组中第一个元素的偏移 |
| numberOfSegments | **int32_t** | 包含在曲线中的段数 |
| tension | **float** | 指定样条张力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) 方法

使用指定的笔绘制样条。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制样条的 pen |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 用于确定样条的点 |
| offset | **int32_t** | **points** 数组中第一个元素的偏移 |
| numberOfSegments | **int32_t** | 包含在曲线中的段数 |
| tension | **float** | 指定样条张力的值 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [Pen](../../pen/)
* 类 [Point](../../point/)
* 类 [Graphics](../)
* 类 [PointF](../../pointf/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)