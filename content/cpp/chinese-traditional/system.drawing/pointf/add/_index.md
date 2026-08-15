---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 SizeF 物件的寬度與高度值分別加入指定的 PointF 物件的 X 與 Y 座標值。
type: docs
weight: 144
url: /zh-hant/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) 方法

將指定的 [SizeF](../../sizef/) 物件的寬度與高度值分別加入指定的 [PointF](../) 物件的 X 與 Y 座標值。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 要平移的點 |
| size | const [SizeF](../../sizef/)\& | 指定要加入 **point** 座標值的 [SizeF](../../sizef/) 物件 |

### 傳回值

傳回一個新的 [PointF](../) 物件，其 X 座標值等於 **point** 的 X 座標值與 **size** 的寬度值之和，Y 座標值等於 **point** 的 Y 座標值與 **size** 的高度值之和。

## PointF::Add(const PointF\&, const Size\&) 方法

將指定的 [Size](../../size/) 物件的寬度與高度值分別加入指定的 [PointF](../) 物件的 X 與 Y 座標值。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | const [PointF](../)\& | 要平移的點 |
| size | const [Size](../../size/)\& | 指定要加入 **point** 座標值的 [Size](../../size/) 物件 |

### 傳回值

傳回一個新的 [PointF](../) 物件，其 X 座標值等於 **point** 的 X 座標值與 **size** 的寬度值之和，Y 座標值等於 **point** 的 Y 座標值與 **size** 的高度值之和。

## 另請參閱

* 類別 [PointF](../)
* 類別 [SizeF](../../sizef/)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)