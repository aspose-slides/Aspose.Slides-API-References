---
title: BeginContainer()
second_title: Aspose.Slides for C++ API 参考
description: 保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。
type: docs
weight: 976
url: /zh/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() 方法


保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) 方法


保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | 指定新容器缩放变换的矩形。与 **srcrect** 一起使用 |
| srcrect | [Rectangle](../../rectangle/) | 指定新容器缩放变换的矩形。与 **dstrect** 一起使用 |
| unit | [GraphicsUnit](../../graphicsunit/) | 指定新容器测量单位的值 |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) 方法


保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | 指定新容器缩放变换的矩形。与 **srcrect** 一起使用 |
| srcrect | [RectangleF](../../rectanglef/) | 指定新容器缩放变换的矩形。与 **dstrect** 一起使用 |
| unit | [GraphicsUnit](../../graphicsunit/) | 指定新容器测量单位的值 |

## 参见

* 枚举 [GraphicsUnit](../../graphicsunit/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 类 [RectangleF](../../rectanglef/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)