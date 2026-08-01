---
title: DrawImage()
second_title: Aspose.Slides voor C++ API-referentie
description: NIET GEREALISEERD.
type: docs
weight: 430
url: /nl/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Genegeerd |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Genegeerd |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Een array met drie punten die een parallellogram op het tekenoppervlak definiëren waarin de afbeelding moet worden getekend |
| srcRect | const [RectangleF](../../rectanglef/)\& | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Een array-view met drie punten die een parallellogram op het tekenoppervlak definiëren waarin de afbeelding moet worden getekend |
| srcRect | const [RectangleF](../../rectanglef/)\& | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Een stack-array met drie punten die een parallellogram op het tekenoppervlak definiëren waarin de afbeelding moet worden getekend |
| srcRect | const [RectangleF](../../rectanglef/)\& | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | int | De X-coördinaat van de linkerbovenhoek van de getekende afbeelding |
| y | int | De Y-coördinaat van de linkerbovenhoek van de getekende afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | **float** | De X-coördinaat van de linkerbovenhoek van de getekende afbeelding |
| y | **float** | De Y-coördinaat van de linkerbovenhoek van de getekende afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| pt | [Point](../../point/) | De locatie van de linkerbovenhoek van de getekende afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| pt | [PointF](../../pointf/) | De locatie van de linkerbovenhoek van de getekende afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) methode

Tekent de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | int | De X-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| y | int | De Y-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| width | int | De breedte van de rechthoek waarin de afbeelding moet worden getekend |
| height | int | De hoogte van de rechthoek waarin de afbeelding moet worden getekend |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) methode

Tekent de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | **float** | De X-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| y | **float** | De Y-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| width | **float** | De breedte van de rechthoek waarin de afbeelding moet worden getekend |
| height | **float** | De hoogte van de rechthoek waarin de afbeelding moet worden getekend |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [RectangleF](../../rectanglef/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcRect | [RectangleF](../../rectanglef/) | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [Rectangle](../../rectangle/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcRect | [Rectangle](../../rectangle/) | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | int | De X-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| y | int | De Y-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| srcRect | [Rectangle](../../rectangle/) | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| rect | const [Rectangle](../../rectangle/)\& | Een rechthoek waarin de afbeelding moet worden getekend |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) methode

Tekent de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| rect | const [RectangleF](../../rectanglef/)\& | Een rechthoek waarin de afbeelding moet worden getekend |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [Rectangle](../../rectangle/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcX | int | De X-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcY | int | De Y-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcWidth | int | De breedte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcHeight | int | De hoogte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden waarin de parameters **srcX**, **srcY**, **srcWidth** en **srcHeight** zijn opgegeven |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [Rectangle](../../rectangle/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcX | **float** | De X-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcY | **float** | De Y-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcWidth | **float** | De breedte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcHeight | **float** | De hoogte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden waarin de parameters **srcX**, **srcY**, **srcWidth** en **srcHeight** zijn opgegeven |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [Rectangle](../../rectangle/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcX | int | De X-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcY | int | De Y-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcWidth | int | De breedte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcHeight | int | De hoogte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden waarin de parameters **srcX**, **srcY**, **srcWidth** en **srcHeight** zijn opgegeven |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding in het opgegeven rechthoek.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destRect | [Rectangle](../../rectangle/) | Een rechthoek waarin de afbeelding moet worden getekend |
| srcX | **float** | De X-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcY | **float** | De Y-coördinaat van de linkerbovenhoek van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcWidth | **float** | De breedte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcHeight | **float** | De hoogte van de rechthoek die het deel van de afbeelding aangeeft dat moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden waarin de parameters **srcX**, **srcY**, **srcWidth** en **srcHeight** zijn opgegeven |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) methode

NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Een array met drie punten die een parallellogram op het tekenoppervlak definiëren waarin de afbeelding moet worden getekend |
| srcRect | [Rectangle](../../rectangle/) | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Specificeert kleuring- en gamma-informatie voor de afbeelding |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) methode

Tekent het opgegeven gebied van de opgegeven afbeelding op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding die moet worden getekend |
| x | **float** | De X-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| y | **float** | De Y-coördinaat van de linkerbovenhoek van de rechthoek waarin de afbeelding moet worden getekend |
| srcRect | [RectangleF](../../rectanglef/) | Een rechthoek die het gebied van de opgegeven afbeelding definieert die moet worden getekend |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | De meeteenheden die worden gebruikt door de parameter **srcRect** |

## Zie ook

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