---
title: Clone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the current object.
type: docs
weight: 183
url: /cpp/system.drawing/bitmap/clone/
---
## Bitmap::Clone() method


Creates a copy of the current object.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Return Value

A copy of the current object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Clone([Rectangle](../../rectangle/), [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/)) method


Creates a [Bitmap](../) object that represents a copy of a region of the bitmap image represented by the current object.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | The rectangle that specifies the region to copy |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | The pixel format for the new [Bitmap](../) |

### Return Value

The created [Bitmap](../) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Clone([RectangleF](../../rectanglef/), [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/)) method


Creates a [Bitmap](../) object that represents a copy of a region of the bitmap image represented by the current object.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | The rectangle that specifies the region to copy |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | The pixel format for the new [Bitmap](../) |

### Return Value

The created [Bitmap](../) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../)
* Class [RectangleF](../../rectanglef/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
