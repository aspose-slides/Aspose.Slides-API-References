---
title: Contains()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的點是否位於當前物件所表示的矩形內。
type: docs
weight: 248
url: /zh-hant/system.drawing/rectanglef/contains/
---
## RectangleF::Contains(float, float) method

判斷指定的點是否位於當前物件所表示的矩形內。

```cpp
bool System::Drawing::RectangleF::Contains(float x, float y)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 要檢查的點的 X 座標 |
| y | **float** | 要檢查的點的 Y 座標 |

### 返回值

如果指定的點位於當前物件所表示的矩形內則返回 True，否則 - false

## RectangleF::Contains(const PointF\&) method

判斷指定的點是否位於當前物件所表示的矩形內。

```cpp
bool System::Drawing::RectangleF::Contains(const PointF &point)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 要檢查的點 |

### 返回值

如果指定的點位於當前物件所表示的矩形內則返回 True，否則 - false

## RectangleF::Contains(const RectangleF\&) method

判斷指定的矩形是否位於當前物件所表示的矩形內。

```cpp
bool System::Drawing::RectangleF::Contains(const RectangleF &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 要檢查的矩形 |

### 返回值

如果指定的矩形位於當前物件所表示的矩形內則返回 True，否則 - false

## 另請參閱

* Class [RectangleF](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)