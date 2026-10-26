---
title: LockBits()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Blokuje bitmapę w pamięci systemowej.
type: docs
weight: 118
url: /pl/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) metoda

Zablokowuje [Bitmap](../) w pamięci systemowej.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt określający obszar obrazu do zablokowania |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Określa poziom dostępu do bitmapy |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format danych tej bitmapy |

### Wartość zwracana

Wskaźnik współdzielony do obiektu BitmapData zawierającego informacje o wykonanej operacji blokowania

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) metoda

Zablokowuje [Bitmap](../) w pamięci systemowej.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt określający obszar obrazu do zablokowania |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Określa poziom dostępu do bitmapy |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format danych tej bitmapy |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Zawiera informacje o operacji blokowania |

### Wartość zwracana

Wskaźnik współdzielony do obiektu BitmapData zawierającego informacje o wykonanej operacji blokowania

## Zobacz także

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Klasa [Rectangle](../../rectangle/)
* Klasa [Bitmap](../)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)