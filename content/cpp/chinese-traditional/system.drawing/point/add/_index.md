---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 Size 物件的寬度和高度值分別加到指定的 Point 物件的 X 與 Y 座標值上。
type: docs
weight: 183
url: /zh-hant/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) 方法

將指定的 [Size](../../size/) 物件的寬度和高度值分別加到指定的 [Point](../) 物件的 X 與 Y 座標值上。

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | 要平移的點 |
| size | const [Size](../../size/)\& | [Size](../../size/) 物件，指定要加到 **point** 座標值的值 |

### 返回值

傳回一個新的 [Point](../) 物件，其 X 座標值等於 **point** 的 X 座標值與 **size** 的寬度值之和，Y 座標值等於 **point** 的 Y 座標值與 **size** 的高度值之和。

## 另請參閱

* 類別 [Point](../)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)