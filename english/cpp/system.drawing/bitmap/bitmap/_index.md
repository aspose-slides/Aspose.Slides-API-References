---
title: Bitmap()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new Bitmap object from the specified existing image.
type: docs
weight: 1
url: /cpp/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\&) constructor


Constructs a new [Bitmap](../) object from the specified existing image.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\&, **bool**) constructor


Constructs a new [Bitmap](../) object from the specified stream.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | A stream that contains image data |
| useIcm | **bool** | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(const [String](../../../system/string/)\&) constructor


Constructs a new [Bitmap](../) object from the specified file.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A name of the file that contains image data |

## See Also

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(const [String](../../../system/string/)\&, **bool**) constructor


Constructs a new [Bitmap](../) object from the specified file.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A name of the file that contains image data |
| useIcm | **bool** | IGNORED |

## See Also

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(int, int, [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/)) constructor


Constructs a new [Bitmap](../) object that represents a bitmap image with the specified width, height, pixel format and pixel data.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the image |
| height | int | The height of the image |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | The pixel format of the image |

## See Also

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\&, const [Size](../../size/)\&) constructor


Constructs a new [Bitmap](../) object from the specified existing image, scaled to the specified size.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |
| size | const [Size](../../size/)\& | The size of the new image |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Size](../../size/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Bitmap::Bitmap(const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\&, int, int) constructor


Constructs a new [Bitmap](../) object from the specified existing image with width and height scaled to the specified values.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |
| width | int | Width of the new image |
| height | int | Height of the new image |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
