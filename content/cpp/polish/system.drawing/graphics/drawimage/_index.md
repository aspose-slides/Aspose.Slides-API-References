---
title: DrawImage()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: NIE ZREALIZOWANO.
type: docs
weight: 430
url: /pl/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNOROWANE |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNOROWANE |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Tablica zawierająca trzy punkty definiujące równoległobok na powierzchni rysowania, na którym ma zostać narysowany obraz |
| srcRect | const [RectangleF](../../rectanglef/)\& | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Widok tablicowy zawierający trzy punkty definiujące równoległobok na powierzchni rysowania, na którym ma zostać narysowany obraz |
| srcRect | const [RectangleF](../../rectanglef/)\& | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Stosowa tablica zawierająca trzy punkty definiujące równoległobok na powierzchni rysowania, na którym ma zostać narysowany obraz |
| srcRect | const [RectangleF](../../rectanglef/)\& | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | int | Współrzędna X lewego górnego rogu rysowanego obrazu |
| y | int | Współrzędna Y lewego górnego rogu rysowanego obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | **float** | Współrzędna X lewego górnego rogu rysowanego obrazu |
| y | **float** | Współrzędna Y lewego górnego rogu rysowanego obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| pt | [Point](../../point/) | Lokalizacja lewego górnego rogu rysowanego obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| pt | [PointF](../../pointf/) | Lokalizacja lewego górnego rogu rysowanego obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metoda


Rysuje określony obraz w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | int | Współrzędna X lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| y | int | Współrzędna Y lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| width | int | Szerokość prostokąta, w którym ma zostać narysowany obraz |
| height | int | Wysokość prostokąta, w którym ma zostać narysowany obraz |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metoda


Rysuje określony obraz w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| width | **float** | Szerokość prostokąta, w którym ma zostać narysowany obraz |
| height | **float** | Wysokość prostokąta, w którym ma zostać narysowany obraz |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [RectangleF](../../rectanglef/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcRect | [RectangleF](../../rectanglef/) | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [Rectangle](../../rectangle/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcRect | [Rectangle](../../rectangle/) | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | int | Współrzędna X lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| y | int | Współrzędna Y lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| srcRect | [Rectangle](../../rectangle/) | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt, w którym ma zostać narysowany obraz |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metoda


Rysuje określony obraz w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| rect | const [RectangleF](../../rectanglef/)\& | Prostokąt, w którym ma zostać narysowany obraz |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Rysuje określony region określonego obrazu w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [Rectangle](../../rectangle/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcX | int | Współrzędna X lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcY | int | Współrzędna Y lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcWidth | int | Szerokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcHeight | int | Wysokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary, w których podane są parametry **srcX**, **srcY**, **srcWidth** i **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metoda


Rysuje określony region określonego obrazu w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [Rectangle](../../rectangle/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcX | **float** | Współrzędna X lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcY | **float** | Współrzędna Y lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcWidth | **float** | Szerokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcHeight | **float** | Wysokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary, w których podane są parametry **srcX**, **srcY**, **srcWidth** i **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [Rectangle](../../rectangle/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcX | int | Współrzędna X lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcY | int | Współrzędna Y lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcWidth | int | Szerokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcHeight | int | Wysokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary, w których podane są parametry **srcX**, **srcY**, **srcWidth** i **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonym prostokącie.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destRect | [Rectangle](../../rectangle/) | Prostokąt, w którym ma zostać narysowany obraz |
| srcX | **float** | Współrzędna X lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcY | **float** | Współrzędna Y lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcWidth | **float** | Szerokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcHeight | **float** | Wysokość lewego górnego rogu prostokąta określającego część obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary, w których podane są parametry **srcX**, **srcY**, **srcWidth** i **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metoda


NIE ZREALIZOWANO.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Tablica zawierająca trzy punkty definiujące równoległobok na powierzchni rysowania, na którym ma zostać narysowany obraz |
| srcRect | [Rectangle](../../rectangle/) | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Określa informacje o kolorowaniu i gamma dla obrazu |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metoda


Rysuje określony region określonego obrazu w określonej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta, w którym ma zostać narysowany obraz |
| srcRect | [RectangleF](../../rectanglef/) | Prostokąt definiujący region wskazanego obrazu do narysowania |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary używane przez parametr **srcRect** |

## Zobacz także

* Wyliczenie [GraphicsUnit](../../graphicsunit/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Definicja typu [DrawImageAbort](../drawimageabort/)
* Klasa [Image](../../image/)
* Klasa [Point](../../point/)
* Klasa [Graphics](../)
* Klasa [PointF](../../pointf/)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [Rectangle](../../rectangle/)
* Klasa [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)