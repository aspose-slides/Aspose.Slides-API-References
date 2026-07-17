---
title: Point()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新的 Point 对象，并将其 X 和 Y 坐标值初始化为 0。
type: docs
weight: 1
url: /zh/system.drawing/point/point/
---
## Point::Point() 构造函数

构造一个新的 [Point](../) 对象，并将其 X 和 Y 坐标值初始化为 0。

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) 构造函数

构造一个新的 [Point](../) 对象，并使用指定的值进行初始化。

```cpp
System::Drawing::Point::Point(int x, int y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | X 坐标的值 |
| y | int | Y 坐标的值 |

## Point::Point(const Size\&) 构造函数

构造一个新的 [Point](../) 对象，并使用指定 [SizeF](../../sizef/) 对象的宽度和高度值分别初始化其 X 和 Y 坐标值。

```cpp
System::Drawing::Point::Point(const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | 用于初始化正在创建的 [Point](../) 对象的 X 和 Y 坐标值的宽度和高度的 [SizeF](../../sizef/) 对象 |

## Point::Point(int) 构造函数

构造一个新的 [Point](../) 对象，并使用指定 32 位整数的高 16 位形成的值初始化其 X 坐标，使用低 16 位形成的值初始化其 Y 坐标。

```cpp
System::Drawing::Point::Point(int dw)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dw | int | 用于创建对象的 32 位整数值，其高 16 位指定 X 坐标值，低 16 位指定 Y 坐标值 |

## 另见

* 类 [Point](../)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)