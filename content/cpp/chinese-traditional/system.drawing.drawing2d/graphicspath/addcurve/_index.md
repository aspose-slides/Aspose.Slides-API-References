---
title: AddCurve()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的曲線新增至目前物件所表示的路徑。
type: docs
weight: 274
url: /zh-hant/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) method


將指定的曲線新增至目前物件所表示的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 指定曲線的點 |
| tension | **float** | 指定曲線在控制點之間彎曲的程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) method


將指定的曲線新增至目前物件所表示的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 指定曲線的點 |
| tension | **float** | 指定曲線在控制點之間彎曲的程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) method


將指定的曲線新增至目前物件所表示的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 指定曲線的點 |
| offset | int | 在 **points** 中用作曲線起始點的點的索引 |
| number_of_segments | int | 繪製曲線所使用的段數 |
| tension | **float** | 指定曲線在控制點之間彎曲的程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) method


將指定的曲線新增至目前物件所表示的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 指定曲線的點 |
| offset | int | 在 **points** 中用作曲線起始點的點的索引 |
| number_of_segments | int | 繪製曲線所使用的段數 |
| tension | **float** | 指定曲線在控制點之間彎曲的程度 |

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [GraphicsPath](../)
* 類別 [Point](../../../system.drawing/point/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)