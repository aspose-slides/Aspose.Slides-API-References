---
title: DrawImage()
second_title: Aspose.Slides pro C++ API Reference
description: NEIMPLEMENTOVÁNO.
type: docs
weight: 430
url: /cs/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORED |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORED |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Pole obsahující tři body, které definují rovnoběžník na kreslicím povrchu, kam se má obrázek vykreslit |
| srcRect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Pohled na pole obsahující tři body, které definují rovnoběžník na kreslicím povrchu, kam se má obrázek vykreslit |
| srcRect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Zásobníkové pole obsahující tři body, které definují rovnoběžník na kreslicím povrchu, kam se má obrázek vykreslit |
| srcRect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | int | Souřadnice X levého horního rohu vykresleného obrázku |
| y | int | Souřadnice Y levého horního rohu vykresleného obrázku |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | **float** | Souřadnice X levého horního rohu vykresleného obrázku |
| y | **float** | Souřadnice Y levého horního rohu vykresleného obrázku |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| pt | [Point](../../point/) | Umístění levého horního rohu vykresleného obrázku |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| pt | [PointF](../../pointf/) | Umístění levého horního rohu vykresleného obrázku |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metoda


Vykreslí zadaný obrázek do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | int | Souřadnice X levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| y | int | Souřadnice Y levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| width | int | Šířka obdélníku, do kterého se má obrázek vykreslit |
| height | int | Výška obdélníku, do kterého se má obrázek vykreslit |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metoda


Vykreslí zadaný obrázek do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | **float** | Souřadnice X levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| y | **float** | Souřadnice Y levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| width | **float** | Šířka obdélníku, do kterého se má obrázek vykreslit |
| height | **float** | Výška obdélníku, do kterého se má obrázek vykreslit |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [RectangleF](../../rectanglef/) | Obdélník, do kterého se má obrázek vykreslit |
| srcRect | [RectangleF](../../rectanglef/) | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [Rectangle](../../rectangle/) | Obdélník, do kterého se má obrázek vykreslit |
| srcRect | [Rectangle](../../rectangle/) | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | int | Souřadnice X levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| y | int | Souřadnice Y levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| srcRect | [Rectangle](../../rectangle/) | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, do kterého se má obrázek vykreslit |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metoda


Vykreslí zadaný obrázek na určené místo.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, do kterého se má obrázek vykreslit |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Vykreslí určený region zadaného obrázku do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [Rectangle](../../rectangle/) | Obdélník, do kterého se má obrázek vykreslit |
| srcX | int | Souřadnice X levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcY | int | Souřadnice Y levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcWidth | int | Šířka části obrázku k vykreslení |
| srcHeight | int | Výška části obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky, ve kterých jsou určeny parametry **srcX**, **srcY**, **srcWidth** a **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Vykreslí určený region zadaného obrázku do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [Rectangle](../../rectangle/) | Obdélník, do kterého se má obrázek vykreslit |
| srcX | **float** | Souřadnice X levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcY | **float** | Souřadnice Y levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcWidth | **float** | Šířka části obrázku k vykreslení |
| srcHeight | **float** | Výška části obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky, ve kterých jsou určeny parametry **srcX**, **srcY**, **srcWidth** a **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [Rectangle](../../rectangle/) | Obdélník, do kterého se má obrázek vykreslit |
| srcX | int | Souřadnice X levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcY | int | Souřadnice Y levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcWidth | int | Šířka části obrázku k vykreslení |
| srcHeight | int | Výška části obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky, ve kterých jsou určeny parametry **srcX**, **srcY**, **srcWidth** a **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku do určeného obdélníku.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destRect | [Rectangle](../../rectangle/) | Obdélník, do kterého se má obrázek vykreslit |
| srcX | **float** | Souřadnice X levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcY | **float** | Souřadnice Y levého horního rohu obdélníku, který určuje část obrázku k vykreslení |
| srcWidth | **float** | Šířka části obrázku k vykreslení |
| srcHeight | **float** | Výška části obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky, ve kterých jsou určeny parametry **srcX**, **srcY**, **srcWidth** a **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metoda


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Pole obsahující tři body, které definují rovnoběžník na kreslicím povrchu, kam se má obrázek vykreslit |
| srcRect | [Rectangle](../../rectangle/) | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Určuje informace o barvách a gamě pro obrázek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metoda


Vykreslí určený region zadaného obrázku na určeném místě.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | **float** | Souřadnice X levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| y | **float** | Souřadnice Y levého horního rohu obdélníku, do kterého se má obrázek vykreslit |
| srcRect | [RectangleF](../../rectanglef/) | Obdélník, který určuje region zadaného obrázku k vykreslení |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky použité parametrem **srcRect** |

## Viz také

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