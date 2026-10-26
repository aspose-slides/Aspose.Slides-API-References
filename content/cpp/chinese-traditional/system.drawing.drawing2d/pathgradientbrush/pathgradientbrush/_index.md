---
title: PathGradientBrush()
second_title: Aspose.Slides for C++ API 參考
description: 建立 PathGradientBrush 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) 建構函式

建立 [PathGradientBrush](../) 類別的新實例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 包含路徑頂點的陣列 |
| wrapMode | [WrapMode](../../wrapmode/) | 指定由被建立之物件所代表的筆刷繪製的填充應如何平鋪 |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) 建構函式

建立 [PathGradientBrush](../) 類別的新實例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 包含路徑頂點的陣列 |
| wrapMode | [WrapMode](../../wrapmode/) | 指定由被建立之物件所代表的筆刷繪製的填充應如何平鋪 |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) 建構函式

建立 [PathGradientBrush](../) 類別的新實例。

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定由被建立之物件填充之路徑的 [GraphicsPath](../../graphicspath/) 物件 |

## 參見

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [PathGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)