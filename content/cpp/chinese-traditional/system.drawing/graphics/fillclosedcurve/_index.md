---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的畫筆繪製封閉樣條曲線。
type: docs
weight: 807
url: /zh-hant/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method

使用指定的畫筆繪製封閉樣條曲線。

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 繪製樣條曲線時使用的畫筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |
| tension | **float** | 指定樣條曲線張力的值 |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method

使用指定的畫筆繪製封閉樣條曲線。

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 繪製樣條曲線時使用的畫筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 用於決定樣條曲線的點 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |
| tension | **float** | 指定樣條曲線張力的值 |

## 另見

* 列舉 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Brush](../../brush/)
* 類別 [PointF](../../pointf/)
* 類別 [Graphics](../)
* 類別 [Point](../../point/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)