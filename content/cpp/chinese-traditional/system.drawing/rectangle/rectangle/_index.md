---
title: Rectangle()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 Rectangle 物件實例，該物件表示一個矩形，其 X 與 Y 座標以及寬度和高度值皆設為 0。
type: docs
weight: 1
url: /zh-hant/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() 建構函式

建立一個新的 [Rectangle](../) 物件實例，該物件表示一個矩形，其 X 與 Y 座標以及寬度和高度值皆設為 0。

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) 建構函式

建立一個新的 [Rectangle](../) 物件實例，該物件表示一個矩形，其左上角的座標以及寬度和高度皆由指定的值決定。

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | 矩形左上角的 X 座標值 |
| y | int | 矩形左上角的 Y 座標值 |
| width | int | 矩形的寬度 |
| height | int | 矩形的高度 |

## Rectangle::Rectangle(const Point\&, const Size\&) 建構函式

建立一個新的 [Rectangle](../) 物件實例，該物件表示一個矩形，其左上角座標以 [Point](../../point/) 類別的實例指定，寬度與高度則以 [Size](../../size/) 類別的實例指定。

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | 指定矩形左上角的位置 |
| size | const [Size](../../size/)\& | 指定矩形的寬度和高度 |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\_&) 建構函式

建立一個新的 [Rectangle](../) 物件實例，該物件表示與指定矩形等價的矩形。

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | 一個 **System::Windows::Forms::Screen::Rectangle_** 類別的實例，用於指定建構之物件所代表的矩形之位置與大小 |

## 另請參閱

* 類別 [Rectangle](../)
* 類別 [Point](../../point/)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)