---
title: Clone()
second_title: Aspose.Slides C++ API 参考
description: 创建当前对象的副本。
type: docs
weight: 183
url: /zh/system.drawing/bitmap/clone/
---
## Bitmap::Clone() 方法

创建当前对象的副本。

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### 返回值

当前对象的副本。

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) 方法

创建一个 [Bitmap](../) 对象，表示由当前对象表示的位图图像的某个区域的副本。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 指定要复制的区域的矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新 [Bitmap](../) 的像素格式 |

### 返回值

创建的 [Bitmap](../) 对象

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) 方法

创建一个 [Bitmap](../) 对象，表示由当前对象表示的位图图像的某个区域的副本。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 指定要复制的区域的矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新 [Bitmap](../) 的像素格式 |

### 返回值

创建的 [Bitmap](../) 对象

## 另请参见

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)