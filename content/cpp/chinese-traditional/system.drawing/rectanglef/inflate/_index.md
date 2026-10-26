---
title: Inflate()
second_title: Aspose.Slides 的 C++ API 參考
description: 將目前物件所代表的矩形的寬度與高度增加，並保持矩形幾何中心的位置。寬度與高度會在兩個方向上依指定的量值增加。
type: docs
weight: 261
url: /zh-hant/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) 方法

將目前物件所代表的矩形的寬度與高度增加，並保持矩形幾何中心的位置。寬度與高度會在兩個方向上依指定的量值增加。

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| width | **float** | 寬度在兩個方向上要增加的量 |
| height | **float** | 高度在兩個方向上要增加的量 |

## RectangleF::Inflate(const SizeF\&) 方法

將目前物件所代表的矩形的寬度與高度增加，並保持矩形幾何中心的位置。寬度與高度會在兩個方向上依照所指定的 SizeF 物件中 width 與 height 值所指定的量分別增加。

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | 指定寬度與高度增加量的 [SizeF](../../sizef/) 物件 |

## RectangleF::Inflate(const RectangleF\&, float, float) 方法

將指定物件所代表的矩形的寬度與高度增加，並保持矩形幾何中心的位置。寬度與高度會在兩個方向上依指定的量值增加。

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 要膨脹的矩形 |
| x | **float** | 寬度在兩個方向上要增加的量 |
| y | **float** | 高度在兩個方向上要增加的量 |

### 傳回值

表示放大後矩形的 [RectangleF](../) 物件

## 相關參考

* 類別 [RectangleF](../)
* 類別 [SizeF](../../sizef/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)