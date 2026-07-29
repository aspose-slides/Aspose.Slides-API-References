---
title: DrawImage()
second_title: Aspose.Slides för C++ API-referens
description: INTE IMPLEMENTERAD.
type: docs
weight: 430
url: /sv/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORERAD |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORERAD |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | En array som innehåller tre punkter som definierar ett parallellogram på ritytan för att rita bilden på |
| srcRect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | En array-vy som innehåller tre punkter som definierar ett parallellogram på ritytan för att rita bilden på |
| srcRect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | En stack-array som innehåller tre punkter som definierar ett parallellogram på ritytan för att rita bilden på |
| srcRect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | int | X-koordinaten för bildens övre vänstra hörn |
| y | int | Y-koordinaten för bildens övre vänstra hörn |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | **float** | X-koordinaten för bildens övre vänstra hörn |
| y | **float** | Y-koordinaten för bildens övre vänstra hörn |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| pt | [Point](../../point/) | Platsen för bildens övre vänstra hörn |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| pt | [PointF](../../pointf/) | Platsen för bildens övre vänstra hörn |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metod


Ritar den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | int | X-koordinaten för rektangelns övre vänstra hörn |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn |
| width | int | Bredden på rektangeln |
| height | int | Höjden på rektangeln |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metod


Ritar den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | **float** | X-koordinaten för rektangelns övre vänstra hörn |
| y | **float** | Y-koordinaten för rektangelns övre vänstra hörn |
| width | **float** | Bredden på rektangeln |
| height | **float** | Höjden på rektangeln |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [RectangleF](../../rectanglef/) | En rektangel att rita bilden i |
| srcRect | [RectangleF](../../rectanglef/) | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [Rectangle](../../rectangle/) | En rektangel att rita bilden i |
| srcRect | [Rectangle](../../rectangle/) | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | int | X-koordinaten för rektangelns övre vänstra hörn |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn |
| srcRect | [Rectangle](../../rectangle/) | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel att rita bilden i |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metod


Ritar den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| rect | const [RectangleF](../../rectanglef/)\& | En rektangel att rita bilden i |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metod


Ritar den angivna regionen av den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [Rectangle](../../rectangle/) | En rektangel att rita bilden i |
| srcX | int | X-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcY | int | Y-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcWidth | int | Bredden på den del av bilden som ska ritas |
| srcHeight | int | Höjden på den del av bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna i vilka parametrarna **srcX**, **srcY**, **srcWidth** och **srcHeight** specificeras |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metod


Ritar den angivna regionen av den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [Rectangle](../../rectangle/) | En rektangel att rita bilden i |
| srcX | **float** | X-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcY | **float** | Y-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcWidth | **float** | Bredden på den del av bilden som ska ritas |
| srcHeight | **float** | Höjden på den del av bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna i vilka parametrarna **srcX**, **srcY**, **srcWidth** och **srcHeight** specificeras |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [Rectangle](../../rectangle/) | En rektangel att rita bilden i |
| srcX | int | X-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcY | int | Y-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcWidth | int | Bredden på den del av bilden som ska ritas |
| srcHeight | int | Höjden på den del av bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna i vilka parametrarna **srcX**, **srcY**, **srcWidth** och **srcHeight** specificeras |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden i den angivna rektangeln.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destRect | [Rectangle](../../rectangle/) | En rektangel att rita bilden i |
| srcX | **float** | X-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcY | **float** | Y-koordinaten för den övre vänstra hörnet av den del av bilden som ska ritas |
| srcWidth | **float** | Bredden på den del av bilden som ska ritas |
| srcHeight | **float** | Höjden på den del av bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna i vilka parametrarna **srcX**, **srcY**, **srcWidth** och **srcHeight** specificeras |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metod


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | En array som innehåller tre punkter som definierar ett parallellogram på ritytan för att rita bilden på |
| srcRect | [Rectangle](../../rectangle/) | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Anger färgläggning och gamma-information för bilden |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metod


Ritar den angivna regionen av den angivna bilden på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | **float** | X-koordinaten för rektangelns övre vänstra hörn |
| y | **float** | Y-koordinaten för rektangelns övre vänstra hörn |
| srcRect | [RectangleF](../../rectanglef/) | En rektangel som definierar området av den angivna bilden som ska ritas |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna som används av parametern **srcRect** |

## Se även

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Klass [Image](../../image/)
* Klass [Point](../../point/)
* Klass [Graphics](../)
* Klass [PointF](../../pointf/)
* Klass [RectangleF](../../rectanglef/)
* Klass [Rectangle](../../rectangle/)
* Klass [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)