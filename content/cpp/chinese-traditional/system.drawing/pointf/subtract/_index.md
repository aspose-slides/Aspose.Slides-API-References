---
title: Subtract()
second_title: Aspose.Slides for C++ API 參考
description: 將指定 SizeF 物件的寬度和高度值分別從指定 PointF 物件的 X 與 Y 座標值中減去。
type: docs
weight: 157
url: /zh-hant/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) 方法

從指定的 [PointF](../) 物件的 X 與 Y 座標值中分別減去指定的 [SizeF](../../sizef/) 物件的寬度與高度值。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | 要平移的點 |
| size | const [SizeF](../../sizef/)\& | 指定從 **point** 座標值中減去之數值的 [SizeF](../../sizef/) 物件 |

### 返回值

一個新的 [PointF](../) 物件，其 X 座標值等於 **size** 的寬度值從 **point** 的 X 座標值減去的結果，且 Y 座標值等於 **size** 的高度值從 **point** 的 Y 座標值減去的結果。

## PointF::Subtract(const PointF\&, const Size\&) 方法

從指定的 [PointF](../) 物件的 X 與 Y 座標值中分別減去指定的 [Size](../../size/) 物件的寬度與高度值。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | 要平移的點 |
| size | const [Size](../../size/)\& | 指定從 **point** 座標值中減去之數值的 [Size](../../size/) 物件 |

### 返回值

一個新的 [PointF](../) 物件，其 X 座標值等於 **size** 的寬度值從 **point** 的 X 座標值減去的結果，且 Y 座標值等於 **size** 的高度值從 **point** 的 Y 座標值減去的結果。

## 另請參閱

* 類別 [PointF](../)
* 類別 [SizeF](../../sizef/)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)