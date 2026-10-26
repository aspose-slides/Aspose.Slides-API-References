---
title: DrawImage()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: غير مُنفَّذ.
type: docs
weight: 430
url: /ar/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | غير مُهتم |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | غير مُهتم |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | مصفوفة تحتوي على ثلاث نقاط تُعرّف متوازي أضلاع على سطح الرسم لرسم الصورة إليه |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | عرض مصفوفة يحتوي على ثلاث نقاط تُعرّف متوازي أضلاع على سطح الرسم لرسم الصورة إليه |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | مصفوفة مكدس تحتوي على ثلاث نقاط تُعرّف متوازي أضلاع على سطح الرسم لرسم الصورة إليه |
| srcRect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | int | إحداثي X للزاوية العلوية اليسرى للصورة المرسومة |
| y | int | إحداثي Y للزاوية العلوية اليسرى للصورة المرسومة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | **float** | إحداثي X للزاوية العلوية اليسرى للصورة المرسومة |
| y | **float** | إحداثي Y للزاوية العلوية اليسرى للصورة المرسومة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| pt | [Point](../../point/) | موقع الزاوية العلوية اليسرى للصورة المرسومة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| pt | [PointF](../../pointf/) | موقع الزاوية العلوية اليسرى للصورة المرسومة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) طريقة

يرسم الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | int | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| y | int | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| width | int | عرض الزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| height | int | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) طريقة

يرسم الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | **float** | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| y | **float** | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| width | **float** | عرض الزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| height | **float** | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [RectangleF](../../rectanglef/) | مستطيل لرسم الصورة إليه |
| srcRect | [RectangleF](../../rectanglef/) | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [Rectangle](../../rectangle/) | مستطيل لرسم الصورة إليه |
| srcRect | [Rectangle](../../rectangle/) | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | int | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| y | int | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| srcRect | [Rectangle](../../rectangle/) | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل لرسم الصورة إليه |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) طريقة

يرسم الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| rect | const [RectangleF](../../rectanglef/)\& | مستطيل لرسم الصورة إليه |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [Rectangle](../../rectangle/) | مستطيل لرسم الصورة إليه |
| srcX | int | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcY | int | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcWidth | int | عرض الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcHeight | int | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس التي تم تحديد فيها المعلمات **srcX**, **srcY**, **srcWidth** و **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [Rectangle](../../rectangle/) | مستطيل لرسم الصورة إليه |
| srcX | **float** | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcY | **float** | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcWidth | **float** | عرض الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcHeight | **float** | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس التي تم تحديد فيها المعلمات **srcX**, **srcY**, **srcWidth** و **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [Rectangle](../../rectangle/) | مستطيل لرسم الصورة إليه |
| srcX | int | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcY | int | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcWidth | int | عرض الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcHeight | int | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس التي تم تحديد فيها المعلمات **srcX**, **srcY**, **srcWidth** و **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة إلى المستطيل المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destRect | [Rectangle](../../rectangle/) | مستطيل لرسم الصورة إليه |
| srcX | **float** | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcY | **float** | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcWidth | **float** | عرض الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcHeight | **float** | ارتفاع الزاوية العلوية اليسرى للمستطيل الذي يحدد الجزء المراد رسمه من الصورة |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس التي تم تحديد فيها المعلمات **srcX**, **srcY**, **srcWidth** و **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) طريقة

غير مُنفَّذ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | مصفوفة تحتوي على ثلاث نقاط تُعرّف متوازي أضلاع على سطح الرسم لرسم الصورة إليه |
| srcRect | [Rectangle](../../rectangle/) | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | يحدد معلومات التلوين والجاما للصورة |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) طريقة

يرسم المنطقة المحددة من الصورة المحددة في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة التي سيتم رسمها |
| x | **float** | إحداثي X للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| y | **float** | إحداثي Y للزاوية العلوية اليسرى للمستطيل الذي سيتم رسم الصورة فيه |
| srcRect | [RectangleF](../../rectanglef/) | مستطيل يحدد منطقة الصورة المحددة للرسم |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | وحدات القياس المستخدمة في المعلمة **srcRect** |

## انظر أيضًا

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