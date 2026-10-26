---
title: Clone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii aktuálního objektu.
type: docs
weight: 183
url: /cs/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metoda


Vytvoří kopii aktuálního objektu.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Návratová hodnota

Kopie aktuálního objektu.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metoda


Vytvoří objekt [Bitmap](../), který představuje kopii oblasti bitmapového obrázku reprezentovaného aktuálním objektem.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Obdélník, který určuje oblast ke zkopírování |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Formát pixelu pro nový [Bitmap](../) |

### Návratová hodnota

Vytvořený objekt [Bitmap](../)

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metoda


Vytvoří objekt [Bitmap](../), který představuje kopii oblasti bitmapového obrázku reprezentovaného aktuálním objektem.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Obdélník, který určuje oblast ke zkopírování |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Formát pixelu pro nový [Bitmap](../) |

### Návratová hodnota

Vytvořený objekt [Bitmap](../)

## Viz také

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)