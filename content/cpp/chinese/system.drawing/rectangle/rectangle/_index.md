---
title: Rectangle()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 Rectangle 对象实例，该对象表示一个矩形，其 X 和 Y 坐标以及宽度和高度值均设置为 0。
type: docs
weight: 1
url: /zh/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() 构造函数

构造一个新的 [Rectangle](../) 对象实例，该对象表示一个矩形，其 X 和 Y 坐标以及宽度和高度值均设置为 0。

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) 构造函数

构造一个新的 [Rectangle](../) 对象实例，该对象表示一个矩形，其左上角的坐标以及宽度和高度均为指定值。

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 矩形左上角的 X 坐标值 |
| y | int | 矩形左上角的 Y 坐标值 |
| width | int | 矩形的宽度 |
| height | int | 矩形的高度 |

## Rectangle::Rectangle(const Point\&, const Size\&) 构造函数

构造一个新的 [Rectangle](../) 对象实例，该对象表示一个矩形，其左上角坐标由 [Point](../../point/) 类的实例指定，宽度和高度由 [Size](../../size/) 类的实例指定。

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | const [Point](../../point/)\& | 指定矩形左上角的位置 |
| size | const [Size](../../size/)\& | 指定矩形的宽度和高度 |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\_\&) 构造函数

构造一个新的 [Rectangle](../) 对象实例，该对象表示等同于指定矩形的矩形。

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | 一个 **System::Windows::Forms::Screen::Rectangle_** 类的实例，指定待构造对象所表示的矩形的位置和大小 |

## 另请参阅

* 类 [Rectangle](../)
* 类 [Point](../../point/)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)