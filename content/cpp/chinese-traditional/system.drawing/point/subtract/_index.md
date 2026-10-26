---
title: Subtract()
second_title: Aspose.Slides C++ API 參考
description: 分別從指定的 Point 物件的 X 與 Y 座標值中減去指定的 Size 物件的寬度與高度值。
type: docs
weight: 196
url: /zh-hant/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) 方法


從指定的 [Point](../) 物件的 X 與 Y 座標值中，分別減去指定的 [Size](../../size/) 物件的寬度與高度值。

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | 要平移的點 |
| size | const [Size](../../size/)\& | 指定要從 **point** 的座標值中減去之值的 [Size](../../size/) 物件 |

### 返回值

一個新的 [Point](../) 物件，其 X 座標值等於 **size** 的寬度值從 **point** 的 X 座標值減去的結果，且 Y 座標值等於 **size** 的高度值從 **point** 的 Y 座標值減去的結果

## 另見

* Class [Point](../)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)