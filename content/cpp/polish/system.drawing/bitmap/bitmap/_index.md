---
title: Bitmap()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy nowy obiekt Bitmap z określonego istniejącego obrazu.
type: docs
weight: 1
url: /pl/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) konstruktor


Tworzy nowy obiekt [Bitmap](../) z określonego istniejącego obrazu.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Istniejący obraz, z którego utworzyć obraz bitmapowy |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) konstruktor


Tworzy nowy obiekt [Bitmap](../) z podanego strumienia.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane obrazu |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) konstruktor


Tworzy nowy obiekt [Bitmap](../) z określonego pliku.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku zawierającego dane obrazu |

## Bitmap::Bitmap(const String\&, bool) konstruktor


Tworzy nowy obiekt [Bitmap](../) z określonego pliku.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku zawierającego dane obrazu |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) konstruktor


Tworzy nowy obiekt [Bitmap](../) reprezentujący obraz bitmapowy o określonych szerokości, wysokości, formacie pikseli i danych pikseli.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| width | int | Szerokość obrazu |
| height | int | Wysokość obrazu |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format pikseli obrazu |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) konstruktor


Tworzy nowy obiekt [Bitmap](../) z określonego istniejącego obrazu, skalowanego do podanego rozmiaru.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Istniejący obraz, z którego utworzyć obraz bitmapowy |
| size | const [Size](../../size/)\& | Rozmiar nowego obrazu |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) konstruktor


Tworzy nowy obiekt [Bitmap](../) z określonego istniejącego obrazu, skalowanego do podanych wartości szerokości i wysokości.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Istniejący obraz, z którego utworzyć obraz bitmapowy |
| width | int | Szerokość nowego obrazu |
| height | int | Wysokość nowego obrazu |

## Zobacz także

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)