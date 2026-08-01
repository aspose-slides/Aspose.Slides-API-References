---
title: LockBits()
second_title: Aspose.Slides for C++ API-referentie
description: Vergrendelt een Bitmap in het systeemgeheugen.
type: docs
weight: 118
url: /nl/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) methode

Vergrendelt een [Bitmap](../) in het systeemgeheugen.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Een rechthoek die het gebied van de afbeelding specificeert dat vergrendeld moet worden |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specificeert het toegangsniveau voor de bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Het gegevensformaat van deze bitmap |

### Retourwaarde

Een gedeelde pointer naar een BitmapData object dat informatie bevat over de uitgevoerde vergrendelingsbewerking

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) methode

Vergrendelt een [Bitmap](../) in het systeemgeheugen.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Een rechthoek die het gebied van de afbeelding specificeert dat vergrendeld moet worden |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specificeert het toegangsniveau voor de bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Het gegevensformaat van deze bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Bevat informatie over de vergrendelingsbewerking |

### Retourwaarde

Een gedeelde pointer naar een BitmapData object dat informatie bevat over de uitgevoerde vergrendelingsbewerking

## Zie ook

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)