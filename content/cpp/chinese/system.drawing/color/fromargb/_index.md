---
title: FromArgb()
second_title: Aspose.Slides for C++ API 参考
description: 构造 Color 类的实例，以表示指定的颜色。
type: docs
weight: 235
url: /zh/system.drawing/color/fromargb/
---
## Color::FromArgb(int) 方法

构造一个 [Color](../) 类的实例，用于表示指定的颜色。

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | int | 一个 32 位 ARGB 值，表示由正在构造的对象所表示的颜色 |

### 返回值

一个表示指定颜色的对象。

## Color::FromArgb(int, int, int, int) 方法

构造一个 [Color](../) 类的实例，用于表示指定的颜色。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | int | 颜色的 alpha 分量的值 |
| red | int | 颜色的红色分量的值 |
| green | int | 颜色的绿色分量的值 |
| blue | int | 颜色的蓝色分量的值 |

### 返回值

一个表示指定颜色的对象。

## Color::FromArgb(int, int, int) 方法

构造一个 [Color](../) 类的实例，用于表示将 alpha 分量设为 0xFF 的指定颜色。

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| red | int | 颜色的红色分量的值 |
| green | int | 颜色的绿色分量的值 |
| blue | int | 颜色的蓝色分量的值 |

### 返回值

一个表示指定颜色的对象。

## Color::FromArgb(int, Color) 方法

构造一个 [Color](../) 类的实例，用于表示指定的颜色。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | int | 颜色的 alpha 分量的值 |
| base_color | [Color](../) | 一个 [Color](../) 对象的实例，表示要由创建的对象所表示的颜色的红、绿、蓝分量 |

### 返回值

一个表示指定颜色的对象。

## 另见

* 类 [Color](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)