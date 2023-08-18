---
title: Clone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the current object.
type: docs
weight: 183
url: /system.drawing/bitmap/clone/
---
## Bitmap::Clone() method


Creates a copy of the current object.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Return Value

A copy of the current object.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) method


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

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) method


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

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)