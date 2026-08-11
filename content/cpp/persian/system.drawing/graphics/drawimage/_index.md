---
title: DrawImage()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی نشده.
type: docs
weight: 430
url: /fa/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | نادیده‌گرفته شد |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | نادیده‌گرفته شد |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | آرایه‌ای شامل سه نقطه که یک موازی‌چین را بر سطح رسم تعریف می‌کند تا تصویر در آن رسم شود |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | نمای آرایه‌ای شامل سه نقطه که یک موازی‌چین را بر سطح رسم تعریف می‌کند تا تصویر در آن رسم شود |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | آرایه پشته‌ای شامل سه نقطه که یک موازی‌چین را بر سطح رسم تعریف می‌کند تا تصویر در آن رسم شود |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | int | مختصات X گوشه بالا سمت چپ تصویر رسم شده |
| y | int | مختصات Y گوشه بالا سمت چپ تصویر رسم شده |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | **float** | مختصات X گوشه بالا سمت چپ تصویر رسم شده |
| y | **float** | مختصات Y گوشه بالا سمت چپ تصویر رسم شده |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| pt | [Point](../../point/) | موقعیت گوشه بالا سمت چپ تصویر رسم شده |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| pt | [PointF](../../pointf/) | موقعیت گوشه بالا سمت چپ تصویر رسم شده |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) method

تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | int | مختصات X گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| y | int | مختصات Y گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| width | int | عرض مستطیلی که تصویر در آن رسم می‌شود |
| height | int | ارتفاع مستطیلی که تصویر در آن رسم می‌شود |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) method

تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | **float** | مختصات X گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| y | **float** | مختصات Y گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| width | **float** | عرض مستطیلی که تصویر در آن رسم می‌شود |
| height | **float** | ارتفاع مستطیلی که تصویر در آن رسم می‌شود |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [RectangleF](../../rectanglef/) | مستطیلی برای رسم تصویر |
| srcRect | [RectangleF](../../rectanglef/) | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [Rectangle](../../rectangle/) | مستطیلی برای رسم تصویر |
| srcRect | [Rectangle](../../rectangle/) | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | int | مختصات X گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| y | int | مختصات Y گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| srcRect | [Rectangle](../../rectangle/) | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| rect | const [Rectangle](../../rectangle/)\& | مستطیلی برای رسم تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) method

تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| rect | const [RectangleF](../../rectanglef/)\& | مستطیلی برای رسم تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [Rectangle](../../rectangle/) | مستطیلی برای رسم تصویر |
| srcX | int | مختصات X گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcY | int | مختصات Y گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcWidth | int | عرض گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcHeight | int | ارتفاع گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری که پارامترهای **srcX**, **srcY**, **srcWidth** و **srcHeight** بر مبنای آنند |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [Rectangle](../../rectangle/) | مستطیلی برای رسم تصویر |
| srcX | **float** | مختصات X گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcY | **float** | مختصات Y گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcWidth | **float** | عرض گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcHeight | **float** | ارتفاع گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری که پارامترهای **srcX**, **srcY**, **srcWidth** و **srcHeight** بر مبنای آنند |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [Rectangle](../../rectangle/) | مستطیلی برای رسم تصویر |
| srcX | int | مختصات X گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcY | int | مختصات Y گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcWidth | int | عرض گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcHeight | int | ارتفاع گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری که پارامترهای **srcX**, **srcY**, **srcWidth** و **srcHeight** بر مبنای آنند |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مستطیل تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destRect | [Rectangle](../../rectangle/) | مستطیلی برای رسم تصویر |
| srcX | **float** | مختصات X گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcY | **float** | مختصات Y گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcWidth | **float** | عرض گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcHeight | **float** | ارتفاع گوشه بالا سمت چپ مستطیلی که بخشی از تصویر برای رسم در آن مشخص می‌شود |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری که پارامترهای **srcX**, **srcY**, **srcWidth** و **srcHeight** بر مبنای آنند |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) method

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | آرایه‌ای شامل سه نقطه که یک موازی‌چین را بر سطح رسم تعریف می‌کند تا تصویر در آن رسم شود |
| srcRect | [Rectangle](../../rectangle/) | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | مشخص می‌کند اطلاعات رنگی و گاما برای تصویر |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) method

ناحیه مشخص‌شده از تصویر مشخص‌شده را در مکان تعیین‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویری که باید رسم شود |
| x | **float** | مختصات X گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| y | **float** | مختصات Y گوشه بالا سمت چپ مستطیلی که تصویر در آن رسم می‌شود |
| srcRect | [RectangleF](../../rectanglef/) | مستطیلی که ناحیه تصویر مشخص‌شده برای رسم را تعریف می‌کند |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری مورد استفاده توسط **srcRect** |

## موارد مرتبط

* شمارش [GraphicsUnit](../../graphicsunit/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* تعریف‌نوع [DrawImageAbort](../drawimageabort/)
* کلاس [Image](../../image/)
* کلاس [Point](../../point/)
* کلاس [Graphics](../)
* کلاس [PointF](../../pointf/)
* کلاس [RectangleF](../../rectanglef/)
* کلاس [Rectangle](../../rectangle/)
* کلاس [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)