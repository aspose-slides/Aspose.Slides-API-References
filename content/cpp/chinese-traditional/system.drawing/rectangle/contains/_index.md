---
title: Contains()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定的點是否位於目前物件所代表的矩形內。
type: docs
weight: 248
url: /zh-hant/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const 方法

判斷指定的點是否位於目前物件所代表的矩形內。

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | int | 要檢查之點的 X 座標 |
| y | int | 要檢查之點的 Y 座標 |

### 回傳值

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Point&) const 方法

判斷指定的點是否位於目前物件所代表的矩形內。

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | 要檢查的點 |

### 回傳值

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Rectangle&) const 方法

判斷指定的矩形是否位於目前物件所代表的矩形內。

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 要檢查的矩形 |

### 回傳值

True if the specified rectangle is located within the rectangle represented by the current object, otherwise - false

## 另請參閱

* Class [Rectangle](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)