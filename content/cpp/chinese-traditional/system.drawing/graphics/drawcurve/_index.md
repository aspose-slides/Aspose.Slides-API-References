---
title: DrawCurve()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的筆繪製樣條曲線。
type: docs
weight: 794
url: /zh-hant/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) 方法

使用指定的筆繪製樣條曲線。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製樣條曲線的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| tension | **float** | 指定樣條曲線張力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) 方法

使用指定的筆繪製樣條曲線。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製樣條曲線的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| tension | **float** | 指定樣條曲線張力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) 方法

使用指定的筆繪製樣條曲線。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製樣條曲線的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| offset | **int32_t** | 從 **points** 陣列的第一個元素的偏移 |
| numberOfSegments | **int32_t** | 要納入曲線的段數 |
| tension | **float** | 指定樣條曲線張力的值 |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) 方法

使用指定的筆繪製樣條曲線。

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製樣條曲線的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| offset | **int32_t** | 從 **points** 陣列的第一個元素的偏移 |
| numberOfSegments | **int32_t** | 要納入曲線的段數 |
| tension | **float** | 指定樣條曲線張力的值 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)