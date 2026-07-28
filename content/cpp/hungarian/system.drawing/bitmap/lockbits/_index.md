---
title: LockBits()
second_title: Aspose.Slides C++ API Referencia
description: Zárol egy Bitmap-et a rendszer memóriájába.
type: docs
weight: 118
url: /hu/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) metódus


Zárol egy [Bitmap](../)-t a rendszer memóriájába.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A téglalap, amely meghatározza a zárolandó kép régióját |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Megadja a bitmap elérési szintjét |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | A bitmap adatformátuma |

### Visszatérési érték

Egy megosztott mutató egy BitmapData objektumra, amely információkat tartalmaz a végrehajtott zárolási műveletről

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) metódus


Zárol egy [Bitmap](../)-t a rendszer memóriájába.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A téglalap, amely meghatározza a zárolandó kép régióját |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Megadja a bitmap elérési szintjét |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | A bitmap adatformátuma |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Információkat tartalmaz a zárolási műveletről |

### Visszatérési érték

Egy megosztott mutató egy BitmapData objektumra, amely információkat tartalmaz a végrehajtott zárolási műveletről

## Lásd még

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)