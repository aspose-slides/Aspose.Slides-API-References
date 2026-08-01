---
title: Clone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van het huidige object.
type: docs
weight: 183
url: /nl/system.drawing/bitmap/clone/
---
## Bitmap::Clone() method


Maakt een kopie van het huidige object.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Retourwaarde

Een kopie van het huidige object.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) method


Maakt een [Bitmap](../) object dat een kopie van een regio van de bitmap-afbeelding vertegenwoordigt die door het huidige object wordt gerepresenteerd.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | De rechthoek die het te kopiëren gebied specificeert |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Het pixelformaat voor de nieuwe [Bitmap](../) |

### Retourwaarde

Het gecreëerde [Bitmap](../) object

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) method


Maakt een [Bitmap](../) object dat een kopie van een regio van de bitmap-afbeelding vertegenwoordigt die door het huidige object wordt gerepresenteerd.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | De rechthoek die het te kopiëren gebied specificeert |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Het pixelformaat voor de nieuwe [Bitmap](../) |

### Retourwaarde

Het gecreëerde [Bitmap](../) object

## Zie ook

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)