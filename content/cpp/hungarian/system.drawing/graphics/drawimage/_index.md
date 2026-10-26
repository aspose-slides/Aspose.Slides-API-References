---
title: DrawImage()
second_title: Aspose.Slides C++ API hivatkozás
description: NINCS MEGVALÓSÍTVA.
type: docs
weight: 430
url: /hu/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metódus

NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | MELLŐZVE |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | MELLŐZVE |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Három pontot tartalmazó tömb, amely egy paralelogrammot definiál a rajzfelületen, ahová a képet rajzolni kell |
| srcRect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Három pontot tartalmazó tömbnézet, amely egy paralelogrammot definiál a rajzfelületen, ahová a képet rajzolni kell |
| srcRect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Három pontot tartalmazó stack tömb, amely egy paralelogrammot definiál a rajzfelületen, ahová a képet rajzolni kell |
| srcRect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | int | A kirajzolt kép bal felső sarkának X koordinátája |
| y | int | A kirajzolt kép bal felső sarkának Y koordinátája |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | **float** | A kirajzolt kép bal felső sarkának X koordinátája |
| y | **float** | A kirajzolt kép bal felső sarkának Y koordinátája |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| pt | [Point](../../point/) | A kirajzolt kép bal felső sarkának helye |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| pt | [PointF](../../pointf/) | A kirajzolt kép bal felső sarkának helye |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | int | A téglalap bal felső sarkának X koordinátája |
| y | int | A téglalap bal felső sarkának Y koordinátája |
| width | int | A téglalap szélessége |
| height | int | A téglalap magassága |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | **float** | A téglalap bal felső sarkának X koordinátája |
| y | **float** | A téglalap bal felső sarkának Y koordinátája |
| width | **float** | A téglalap szélessége |
| height | **float** | A téglalap magassága |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [RectangleF](../../rectanglef/) | Egy téglalap, ahová a képet rajzolni kell |
| srcRect | [RectangleF](../../rectanglef/) | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [Rectangle](../../rectangle/) | Egy téglalap, ahová a képet rajzolni kell |
| srcRect | [Rectangle](../../rectangle/) | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | int | A téglalap bal felső sarkának X koordinátája |
| y | int | A téglalap bal felső sarkának Y koordinátája |
| srcRect | [Rectangle](../../rectangle/) | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| rect | const [Rectangle](../../rectangle/)\& | Egy téglalap, ahová a képet rajzolni kell |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metódus


A megadott helyen rajzolja a megadott képet.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| rect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, ahová a képet rajzolni kell |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [Rectangle](../../rectangle/) | Egy téglalap, ahová a képet rajzolni kell |
| srcX | int | A rajzolandó kép részét meghatározó téglalap bal felső sarkának X koordinátája |
| srcY | int | A rajzolandó kép részét meghatározó téglalap bal felső sarkának Y koordinátája |
| srcWidth | int | A rajzolandó kép részét meghatározó téglalap szélessége |
| srcHeight | int | A rajzolandó kép részét meghatározó téglalap magassága |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcX**, **srcY**, **srcWidth** és **srcHeight** paraméterekben használt mérési egységek |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [Rectangle](../../rectangle/) | Egy téglalap, ahová a képet rajzolni kell |
| srcX | **float** | A rajzolandó kép részét meghatározó téglalap bal felső sarkának X koordinátája |
| srcY | **float** | A rajzolandó kép részét meghatározó téglalap bal felső sarkának Y koordinátája |
| srcWidth | **float** | A rajzolandó kép részét meghatározó téglalap szélessége |
| srcHeight | **float** | A rajzolandó kép részét meghatározó téglalap magassága |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcX**, **srcY**, **srcWidth** és **srcHeight** paraméterekben használt mérési egységek |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [Rectangle](../../rectangle/) | Egy téglalap, ahová a képet rajzolni kell |
| srcX | int | A rajzolandó kép részét meghatározó téglalap bal felső sarkának X koordinátája |
| srcY | int | A rajzolandó kép részét meghatározó téglalap bal felső sarkának Y koordinátája |
| srcWidth | int | A rajzolandó kép részét meghatározó téglalap szélessége |
| srcHeight | int | A rajzolandó kép részét meghatározó téglalap magassága |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcX**, **srcY**, **srcWidth** és **srcHeight** paraméterekben használt mérési egységek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metódus


A megadott képet a megadott téglalapba rajzolja.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destRect | [Rectangle](../../rectangle/) | Egy téglalap, ahová a képet rajzolni kell |
| srcX | **float** | A rajzolandó kép részét meghatározó téglalap bal felső sarkának X koordinátája |
| srcY | **float** | A rajzolandó kép részét meghatározó téglalap bal felső sarkának Y koordinátája |
| srcWidth | **float** | A rajzolandó kép részét meghatározó téglalap szélessége |
| srcHeight | **float** | A rajzolandó kép részét meghatározó téglalap magassága |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcX**, **srcY**, **srcWidth** és **srcHeight** paraméterekben használt mérési egységek |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metódus


NEM VALÓSÍTOTT.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Három pontot tartalmazó tömb, amely egy paralelogrammot definiál a rajzfelületen, ahová a képet rajzolni kell |
| srcRect | [Rectangle](../../rectangle/) | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | A kép színezését és gamma információit adja meg |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metódus


A megadott helyen rajzolja a megadott kép megadott régióját.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | **float** | A téglalap bal felső sarkának X koordinátája |
| y | **float** | A téglalap bal felső sarkának Y koordinátája |
| srcRect | [RectangleF](../../rectanglef/) | Egy téglalap, amely meghatározza a megadott kép rajzolandó régióját |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | A **srcRect** paraméterben használt mérési egységek |

## Lásd még

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Osztály [Image](../../image/)
* Osztály [Point](../../point/)
* Osztály [Graphics](../)
* Osztály [PointF](../../pointf/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [Rectangle](../../rectangle/)
* Osztály [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)