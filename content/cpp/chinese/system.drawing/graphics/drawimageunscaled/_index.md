---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API 参考
description: 在指定位置使用原始物理尺寸绘制指定的图像。
type: docs
weight: 443
url: /zh/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) 方法

在指定位置使用原始物理尺寸绘制指定的图像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | int | 绘制图像左上角的 X 坐标 |
| y | int | 绘制图像左上角的 Y 坐标 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) 方法

在指定位置使用原始物理尺寸绘制指定的图像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | int | 绘制图像左上角的 X 坐标 |
| y | int | 绘制图像左上角的 Y 坐标 |
| width | int | 未使用 |
| height | int | 未使用 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) 方法

在指定位置使用原始物理尺寸绘制指定的图像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| rect | const [Rectangle](../../rectangle/)\& | 指定绘制图像左上角的矩形。矩形的 X 和 Y 属性指定左上角。宽度和高度值被忽略。 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) 方法

在指定位置使用原始物理尺寸绘制指定的图像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| point | const [Point](../../point/)\& | 指定绘制图像左上角的 [Point](../../point/) 结构。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Image](../../image/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 类 [Point](../../point/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)