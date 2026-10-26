---
title: Point()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的 Point 物件，並將其 X 與 Y 座標值初始化為 0。
type: docs
weight: 1
url: /zh-hant/system.drawing/point/point/
---
## Point::Point() 建構子

建構一個新的 [Point](../) 物件，並將其 X 與 Y 座標的值初始化為 0。

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) 建構子

建構一個新的 [Point](../) 物件，並以指定的值進行初始化。

```cpp
System::Drawing::Point::Point(int x, int y)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | X 座標的值 |
| y | int | Y 座標的值 |

## Point::Point(const Size\&) 建構子

建構一個新的 [Point](../) 物件，並以指定的 [SizeF](../../sizef/) 物件的寬度與高度值分別初始化其 X 與 Y 座標值。

```cpp
System::Drawing::Point::Point(const Size &size)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | 一個 [SizeF](../../sizef/) 物件，其寬度與高度值用於初始化正在建立的 [Point](../) 物件的 X 與 Y 座標值 |

## Point::Point(int) 建構子

建構一個新的 [Point](../) 物件，並以指定的 32 位元整數之高 16 位元形成的值初始化其 X 座標，以低 16 位元形成的值初始化其 Y 座標。

```cpp
System::Drawing::Point::Point(int dw)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dw | int | 這個 32 位元整數的高 16 位元指定 X 座標值，低 16 位元指定正在建立的物件的 Y 座標值 |

## 另請參閱

* 類別 [Point](../)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)