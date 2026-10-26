---
title: Clone()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot a jelenlegi objektumról.
type: docs
weight: 183
url: /hu/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metódus

Létrehoz egy másolatot a jelenlegi objektumról.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Visszatérési érték

A jelenlegi objektum másolata.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metódus

Létrehoz egy [Bitmap](../) objektumot, amely a jelenlegi objektum által képviselt bitmap kép egy régiójának másolatát ábrázolja.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | A másolandó régiót meghatározó téglalap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Az új [Bitmap](../) képpontformátuma |

### Visszatérési érték

A létrehozott [Bitmap](../) objektum

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metódus

Létrehoz egy [Bitmap](../) objektumot, amely a jelenlegi objektum által képviselt bitmap kép egy régiójának másolatát ábrázolja.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | A másolandó régiót meghatározó téglalap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Az új [Bitmap](../) képpontformátuma |

### Visszatérési érték

A létrehozott [Bitmap](../) objektum

## Lásd még

* Enumeráció [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Image](../../image/)
* Osztály [Bitmap](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [RectangleF](../../rectanglef/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)