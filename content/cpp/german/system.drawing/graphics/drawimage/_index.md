---
title: DrawImage()
second_title: Aspose.Slides für C++ API-Referenz
description: NICHT IMPLEMENTIERT.
type: docs
weight: 430
url: /de/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORIERT |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORIERT |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Ein Array, das drei Punkte enthält, die ein Parallelogramm auf der Zeichenfläche definieren, in das das Bild gezeichnet wird |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Eine Array-Ansicht, die drei Punkte enthält, die ein Parallelogramm auf der Zeichenfläche definieren, in das das Bild gezeichnet wird |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Ein Stack-Array, das drei Punkte enthält, die ein Parallelogramm auf der Zeichenfläche definieren, in das das Bild gezeichnet wird |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | int | Die X-Koordinate der oberen linken Ecke des gezeichneten Bildes |
| y | int | Die Y-Koordinate der oberen linken Ecke des gezeichneten Bildes |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | **float** | Die X-Koordinate der oberen linken Ecke des gezeichneten Bildes |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des gezeichneten Bildes |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| pt | [Point](../../point/) | Die Position der oberen linken Ecke des gezeichneten Bildes |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| pt | [PointF](../../pointf/) | Die Position der oberen linken Ecke des gezeichneten Bildes |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) Methode


Zeichnet das angegebene Bild in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | int | Die X-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| y | int | Die Y-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| width | int | Die Breite des Rechtecks, in das das Bild gezeichnet wird |
| height | int | Die Höhe des Rechtecks, in das das Bild gezeichnet wird |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) Methode


Zeichnet das angegebene Bild in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| width | **float** | Die Breite des Rechtecks, in das das Bild gezeichnet wird |
| height | **float** | Die Höhe des Rechtecks, in das das Bild gezeichnet wird |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [RectangleF](../../rectanglef/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcRect | [RectangleF](../../rectanglef/) | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [Rectangle](../../rectangle/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcRect | [Rectangle](../../rectangle/) | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | int | Die X-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| y | int | Die Y-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| srcRect | [Rectangle](../../rectangle/) | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, in das das Bild gezeichnet wird |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) Methode


Zeichnet das angegebene Bild an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, in das das Bild gezeichnet wird |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [Rectangle](../../rectangle/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcX | int | Die X-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcY | int | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcWidth | int | Die Breite des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcHeight | int | Die Höhe des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheiten, in denen die Parameter **srcX**, **srcY**, **srcWidth** und **srcHeight** angegeben sind |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [Rectangle](../../rectangle/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcX | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcY | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcWidth | **float** | Die Breite des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcHeight | **float** | Die Höhe des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheiten, in denen die Parameter **srcX**, **srcY**, **srcWidth** und **srcHeight** angegeben sind |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [Rectangle](../../rectangle/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcX | int | Die X-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcY | int | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcWidth | int | Die Breite des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcHeight | int | Die Höhe des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheiten, in denen die Parameter **srcX**, **srcY**, **srcWidth** und **srcHeight** angegeben sind |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes in das angegebene Rechteck.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destRect | [Rectangle](../../rectangle/) | Ein Rechteck, in das das Bild gezeichnet wird |
| srcX | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcY | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcWidth | **float** | Die Breite des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcHeight | **float** | Die Höhe des Rechtecks, das den zu zeichnenden Bildausschnitt definiert |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die Maßeinheiten, in denen die Parameter **srcX**, **srcY**, **srcWidth** und **srcHeight** angegeben sind |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) Methode


NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Ein Array, das drei Punkte enthält, die ein Parallelogramm auf der Zeichenfläche definieren, in das das Bild gezeichnet wird |
| srcRect | [Rectangle](../../rectangle/) | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Gibt die Farb- und Gammainformationen für das Bild an |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) Methode


Zeichnet den angegebenen Bereich des angegebenen Bildes an der angegebenen Position.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Parameter

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, in das das Bild gezeichnet wird |
| srcRect | [RectangleF](../../rectanglef/) | Ein Rechteck, das den Bereich des angegebenen Bildes definiert, der gezeichnet werden soll |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Die von dem Parameter **srcRect** verwendeten Maßeinheiten |

## Siehe auch

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