---
title: LockBits()
second_title: Aspose.Slides for C++ API Reference
description: Locks a Bitmap into system memory.
type: docs
weight: 118
url: /cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Locks a [Bitmap](../) into system memory.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that specifies the region of the image to lock |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specifies the access level to the bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | The data format of this bitmap |

### Return Value

A shared pointer to a BitmapData object that contains information about the performed lock operation

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Locks a [Bitmap](../) into system memory.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that specifies the region of the image to lock |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specifies the access level to the bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | The data format of this bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Contains information about the lock operation |

### Return Value

A shared pointer to a BitmapData object that contains information about the performed lock operation

## See Also

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)