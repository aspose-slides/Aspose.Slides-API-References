---
title: Inflate()
second_title: Aspose.Slides for C++ API 參考
description: 增加目前物件所代表的矩形的寬度和高度，維持該矩形幾何中心的位置。寬度和高度會在兩個方向上以指定的量增加。
type: docs
weight: 261
url: /zh-hant/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) 方法

增加目前物件所代表的 Rectangle 的寬度和高度，維持該幾何中心的位置。寬度和高度會在兩個方向上以指定的量增加。

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | int | 在兩個方向上 width 要增加的量 |
| height | int | 在兩個方向上 height 要增加的量 |

## Rectangle::Inflate(const Size\&) 方法

增加目前物件所代表的 Rectangle 的寬度和高度，維持該幾何中心的位置。寬度和高度會在兩個方向上以指定的 size 物件中 width 與 height 值分別增加的量。

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | 用於指定寬度和高度增加量的 [Size](../../size/) 物件 |

## Rectangle::Inflate(const Rectangle\&, int, int) 方法

增加指定物件所代表的 Rectangle 的寬度和高度，維持該幾何中心的位置。寬度和高度會在兩個方向上以指定的量增加。

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 要膨脹的 Rectangle |
| x | int | 在兩個方向上 width 要增加的量 |
| y | int | 在兩個方向上 height 要增加的量 |

### 回傳值

代表放大後 Rectangle 的 [Rectangle](../) 物件

## 另請參閱

* 類別 [Rectangle](../)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)