---
title: LockBits()
second_title: Aspose.Slides für C++ API-Referenz
description: Sperrt ein Bitmap in den Systemspeicher.
type: docs
weight: 118
url: /de/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) Methode

Sperrt ein [Bitmap](../) in den Systemspeicher.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das den Bereich des Bildes angibt, der gesperrt werden soll |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Gibt die Zugriffsberechtigung für das Bitmap an |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Das Datenformat dieses Bitmaps |

### Return Value

Ein Shared Pointer auf ein BitmapData-Objekt, das Informationen über den ausgeführten Sperrvorgang enthält

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) Methode

Sperrt ein [Bitmap](../) in den Systemspeicher.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das den Bereich des Bildes angibt, der gesperrt werden soll |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Gibt die Zugriffsberechtigung für das Bitmap an |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Das Datenformat dieses Bitmaps |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Enthält Informationen über den Sperrvorgang |

### Return Value

Ein Shared Pointer auf ein BitmapData-Objekt, das Informationen über den ausgeführten Sperrvorgang enthält

## Siehe auch

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Klasse [Rectangle](../../rectangle/)
* Klasse [Bitmap](../)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)