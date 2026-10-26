---
title: Clone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av det aktuella objektet.
type: docs
weight: 183
url: /sv/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metod

Skapar en kopia av det aktuella objektet.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Returvärde

En kopia av det aktuella objektet.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metod

Skapar ett [Bitmap](../)-objekt som representerar en kopia av en region av bitmap-bilden som representeras av det aktuella objektet.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Rektangeln som specificerar regionen att kopiera |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Pixelformatet för den nya [Bitmap](../) |

### Returvärde

Det skapade [Bitmap](../)-objektet

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metod

Skapar ett [Bitmap](../)-objekt som representerar en kopia av en region av bitmap-bilden som representeras av det aktuella objektet.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Rektangeln som specificerar regionen att kopiera |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Pixelformatet för den nya [Bitmap](../) |

### Returvärde

Det skapade [Bitmap](../)-objektet

## Se även

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Image](../../image/)
* Klass [Bitmap](../)
* Klass [Rectangle](../../rectangle/)
* Klass [RectangleF](../../rectanglef/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)