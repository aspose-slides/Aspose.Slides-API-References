---
title: LockBits()
second_title: Aspose.Slides pro C++ – API reference
description: Uzamkne Bitmap do systémové paměti.
type: docs
weight: 118
url: /cs/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) metoda


Uzamkne [Bitmap](../) do systémové paměti.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje oblast obrázku k uzamčení |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Určuje úroveň přístupu k bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Datový formát této bitmap |

### Návratová hodnota

Sdílený ukazatel na objekt BitmapData, který obsahuje informace o provedené operaci uzamčení

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) metoda


Uzamkne [Bitmap](../) do systémové paměti.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje oblast obrázku k uzamčení |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Určuje úroveň přístupu k bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Datový formát této bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Obsahuje informace o operaci uzamčení |

### Návratová hodnota

Sdílený ukazatel na objekt BitmapData, který obsahuje informace o provedené operaci uzamčení

## Viz také

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)