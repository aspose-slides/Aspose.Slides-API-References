---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的筆繪製封閉樣條。
type: docs
weight: 781
url: /zh-hant/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) 方法

使用指定的筆繪製封閉樣條。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製樣條時使用的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 的點，用於決定樣條 |
| tension | **float** | 指定樣條張力的值 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) 方法

使用指定的筆繪製封閉樣條。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製樣條時使用的筆 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 的點，用於決定樣條 |
| tension | **float** | 指定樣條張力的值 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |

## 相關參考

* 列舉 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Pen](../../pen/)
* 類別 [Point](../../point/)
* 類別 [Graphics](../)
* 類別 [PointF](../../pointf/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)