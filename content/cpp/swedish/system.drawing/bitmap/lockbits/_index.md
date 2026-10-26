---
title: LockBits()
second_title: Aspose.Slides för C++ API-referens
description: Låser en Bitmap i systemminnet.
type: docs
weight: 118
url: /sv/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) metod

Låser en [Bitmap](../) i systemminnet.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel som specificerar regionen av bilden som ska låsas |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specificerar åtkomstnivån till bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Dataformatet för denna bitmap |

### Returvärde

En gemensam pekare till ett BitmapData-objekt som innehåller information om den utförda låsningsoperationen

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) metod

Låser en [Bitmap](../) i systemminnet.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel som specificerar regionen av bilden som ska låsas |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specificerar åtkomstnivån till bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Dataformatet för denna bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Innehåller information om låsningsoperationen |

### Returvärde

En gemensam pekare till ett BitmapData-objekt som innehåller information om den utförda låsningsoperationen

## Se även

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)