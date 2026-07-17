---
title: DrawImage()
second_title: Aspose.Slides for C++ API 参考
description: 未实现。
type: docs
weight: 430
url: /zh/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 已忽略 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 已忽略 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 一个包含三个点的数组，这三个点定义了绘图表面上的一个平行四边形，用于绘制图像 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | 一个包含三个点的数组视图，这三个点定义了绘图表面上的一个平行四边形，用于绘制图像 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

在指定位置绘制指定图像的指定区域。

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | 一个堆栈数组，包含三个点，这些点定义了绘图表面上的平行四边形，用于绘制图像 |
| srcRect | const [RectangleF](../../rectanglef/)\& | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | int | 绘制图像左上角的 X 坐标 |
| y | int | 绘制图像左上角的 Y 坐标 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | **float** | 绘制图像左上角的 X 坐标 |
| y | **float** | 绘制图像左上角的 Y 坐标 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| pt | [Point](../../point/) | 绘制图像左上角的位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| pt | [PointF](../../pointf/) | 绘制图像左上角的位置 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) method

将指定图像绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | int | 绘制图像的矩形左上角的 X 坐标 |
| y | int | 绘制图像的矩形左上角的 Y 坐标 |
| width | int | 绘制图像的矩形的宽度 |
| height | int | 绘制图像的矩形的高度 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) method

将指定图像绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | **float** | 绘制图像的矩形左上角的 X 坐标 |
| y | **float** | 绘制图像的矩形左上角的 Y 坐标 |
| width | **float** | 绘制图像的矩形的宽度 |
| height | **float** | 绘制图像的矩形的高度 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [RectangleF](../../rectanglef/) | 用于绘制图像的矩形 |
| srcRect | [RectangleF](../../rectanglef/) | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [Rectangle](../../rectangle/) | 用于绘制图像的矩形 |
| srcRect | [Rectangle](../../rectangle/) | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | int | 绘制图像的矩形左上角的 X 坐标 |
| y | int | 绘制图像的矩形左上角的 Y 坐标 |
| srcRect | [Rectangle](../../rectangle/) | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| rect | const [Rectangle](../../rectangle/)\& | 用于绘制图像的矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) method

在指定位置绘制指定图像。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| rect | const [RectangleF](../../rectanglef/)\& | 用于绘制图像的矩形 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

将指定图像的指定区域绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [Rectangle](../../rectangle/) | 用于绘制图像的矩形 |
| srcX | int | 指定要绘制的图像部分的矩形左上角的 X 坐标 |
| srcY | int | 指定要绘制的图像部分的矩形左上角的 Y 坐标 |
| srcWidth | int | 指定要绘制的图像部分的矩形的宽度 |
| srcHeight | int | 指定要绘制的图像部分的矩形的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | 参数 **srcX**、**srcY**、**srcWidth** 和 **srcHeight** 所使用的度量单位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

将指定图像的指定区域绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [Rectangle](../../rectangle/) | 用于绘制图像的矩形 |
| srcX | **float** | 指定要绘制的图像部分的矩形左上角的 X 坐标 |
| srcY | **float** | 指定要绘制的图像部分的矩形左上角的 Y 坐标 |
| srcWidth | **float** | 指定要绘制的图像部分的矩形的宽度 |
| srcHeight | **float** | 指定要绘制的图像部分的矩形的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | 参数 **srcX**、**srcY**、**srcWidth** 和 **srcHeight** 所使用的度量单位 |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) method

将指定图像的指定区域绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [Rectangle](../../rectangle/) | 用于绘制图像的矩形 |
| srcX | int | 指定要绘制的图像部分的矩形左上角的 X 坐标 |
| srcY | int | 指定要绘制的图像部分的矩形左上角的 Y 坐标 |
| srcWidth | int | 指定要绘制的图像部分的矩形的宽度 |
| srcHeight | int | 指定要绘制的图像部分的矩形的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | 参数 **srcX**、**srcY**、**srcWidth** 和 **srcHeight** 所使用的度量单位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) method

将指定图像的指定区域绘制到指定矩形。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destRect | [Rectangle](../../rectangle/) | 用于绘制图像的矩形 |
| srcX | **float** | 指定要绘制的图像部分的矩形左上角的 X 坐标 |
| srcY | **float** | 指定要绘制的图像部分的矩形左上角的 Y 坐标 |
| srcWidth | **float** | 指定要绘制的图像部分的矩形的宽度 |
| srcHeight | **float** | 指定要绘制的图像部分的矩形的高度 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | 参数 **srcX**、**srcY**、**srcWidth** 和 **srcHeight** 所使用的度量单位 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) method

未实现。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 一个包含三个点的数组，这三个点定义了绘图表面上的一个平行四边形，用于绘制图像 |
| srcRect | [Rectangle](../../rectangle/) | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 指定图像的着色和伽马信息 |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) method

在指定位置绘制指定图像的指定区域。

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要绘制的图像 |
| x | **float** | 绘制图像的矩形左上角的 X 坐标 |
| y | **float** | 绘制图像的矩形左上角的 Y 坐标 |
| srcRect | [RectangleF](../../rectanglef/) | 一个矩形，定义要绘制的指定图像的区域 |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | **srcRect** 参数使用的度量单位 |

## 另请参阅

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)