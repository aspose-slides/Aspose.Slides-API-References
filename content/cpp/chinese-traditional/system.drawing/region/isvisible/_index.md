---
title: IsVisible()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的點是否位於目前物件所表示的區域內。
type: docs
weight: 196
url: /zh-hant/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const method


判斷指定的點是否位於目前物件所表示的區域內。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 待檢查的點 |

## Region::IsVisible(const PointF\&) const method


判斷指定的點是否位於目前物件所表示的區域內。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 待檢查的點 |

## Region::IsVisible(const Rectangle\&) method


判斷指定的矩形的任何部分是否位於目前物件所表示的區域內。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 待檢查的矩形 |

## Region::IsVisible(const RectangleF\&) method


判斷指定的矩形的任何部分是否位於目前物件所表示的區域內。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 待檢查的矩形 |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const method


判斷指定的點是否位於目前物件所表示的區域內，並使用指定的圖形。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 待檢查的點 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 圖形上下文 |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const method


判斷指定的點是否位於目前物件所表示的區域內，並使用指定的圖形。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 待檢查的點 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 圖形上下文 |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) method


判斷指定的矩形的任何部分是否位於目前物件所表示的區域內，並使用指定的圖形。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 待檢查的矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 圖形上下文 |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) method


判斷指定的矩形的任何部分是否位於目前物件所表示的區域內，並使用指定的圖形。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 待檢查的矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 圖形上下文 |

## Region::IsVisible(float, float) const method


判斷指定的點是否位於目前物件所表示的區域內。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 待檢查的點的 X 座標 |
| y | **float** | 待檢查的點的 Y 座標 |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const method


判斷指定的點是否位於目前物件所表示的區域內，並使用指定的圖形。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 待檢查的點的 X 座標 |
| y | **float** | 待檢查的點的 Y 座標 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 圖形上下文 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Point](../../point/)
* 類別 [Region](../)
* 類別 [PointF](../../pointf/)
* 類別 [Rectangle](../../rectangle/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Graphics](../../graphics/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)