---
title: DrawImage()
second_title: Aspose.Slides for C++ API Reference
description: NOT IMPLEMENTED.
type: docs
weight: 430
url: /cpp/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORED |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORED |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | An array containing three points that define a parallelogram on the drawing surface to draw the image to |
| srcRect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | An array view containing three points that define a parallelogram on the drawing surface to draw the image to |
| srcRect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method


Draws the specified region of the specified image at the specified location.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | An stack array containing three points that define a parallelogram on the drawing surface to draw the image to |
| srcRect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | int | The X coordinate of the upper left corner of the drawn image |
| y | int | The Y coordinate of the upper left corner of the drawn image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | **float** | The X coordinate of the upper left corner of the drawn image |
| y | **float** | The Y coordinate of the upper left corner of the drawn image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| pt | [Point](../../point/) | The location of the upper left corner of the drawn image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| pt | [PointF](../../pointf/) | The location of the upper left corner of the drawn image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) method


Draws the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | int | The X coordinate of the upper left corner of the rectangle to draw the image to |
| y | int | The Y coordinate of the upper left corner of the rectangle to draw the image to |
| width | int | The width of the upper left corner of the rectangle to draw the image to |
| height | int | The height of the upper left corner of the rectangle to draw the image to |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) method


Draws the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | **float** | The X coordinate of the upper left corner of the rectangle to draw the image to |
| y | **float** | The Y coordinate of the upper left corner of the rectangle to draw the image to |
| width | **float** | The width of the upper left corner of the rectangle to draw the image to |
| height | **float** | The height of the upper left corner of the rectangle to draw the image to |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [RectangleF](../../rectanglef/) | A rectangle to draw the image to |
| srcRect | [RectangleF](../../rectanglef/) | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [Rectangle](../../rectangle/) | A rectangle to draw the image to |
| srcRect | [Rectangle](../../rectangle/) | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | int | The X coordinate of the upper left corner of the rectangle to draw the image to |
| y | int | The Y coordinate of the upper left corner of the rectangle to draw the image to |
| srcRect | [Rectangle](../../rectangle/) | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle to draw the image to |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) method


Draws the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle to draw the image to |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method


Draws the specified region of the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [Rectangle](../../rectangle/) | A rectangle to draw the image to |
| srcX | int | The X coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcY | int | The Y coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcWidth | int | The width of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcHeight | int | The height of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units in which parameters **srcX**, **srcY**, **srcWidth** and **srcHeight** are specified |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method


Draws the specified region of the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [Rectangle](../../rectangle/) | A rectangle to draw the image to |
| srcX | **float** | The X coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcY | **float** | The Y coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcWidth | **float** | The width of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcHeight | **float** | The height of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units in which parameters **srcX**, **srcY**, **srcWidth** and **srcHeight** are specified |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) method


Draws the specified region of the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [Rectangle](../../rectangle/) | A rectangle to draw the image to |
| srcX | int | The X coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcY | int | The Y coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcWidth | int | The width of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcHeight | int | The height of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units in which parameters **srcX**, **srcY**, **srcWidth** and **srcHeight** are specified |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) method


Draws the specified region of the specified image to the specified rectangle.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destRect | [Rectangle](../../rectangle/) | A rectangle to draw the image to |
| srcX | **float** | The X coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcY | **float** | The Y coordinate of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcWidth | **float** | The width of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcHeight | **float** | The height of the upper left corner of the rectangle that specifies the portion of the image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units in which parameters **srcX**, **srcY**, **srcWidth** and **srcHeight** are specified |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | An array containing three points that define a parallelogram on the drawing surface to draw the image to |
| srcRect | [Rectangle](../../rectangle/) | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Specifies coloring and gamma information for the image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) method


Draws the specified region of the specified image at the specified location.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | **float** | The X coordinate of the upper left corner of the rectangle to draw the image to |
| y | **float** | The Y coordinate of the upper left corner of the rectangle to draw the image to |
| srcRect | [RectangleF](../../rectanglef/) | A rectangle that defines the region of the specified image to draw |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | The measurement units used by **srcRect** parameter |

## See Also

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