---
title: AddImage()
second_title: Aspose.Slides for C++ API Reference
description: Add an image to a presentation.
type: docs
weight: 14
url: /aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<System::Drawing::Image\>) method


Add an image to a presentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::Drawing::Image> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Image](../../../system.drawing/image/)\> | Image to add. |

### Return Value

Added image.
## Remarks


Deprecated
:   Use AddImage(IImage image) method instead. The method will be removed after release of version 24.7.


This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation.

## IImageCollection::AddImage(System::SharedPtr\<IImage\>) method


Add an image to a presentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image to add. |

### Return Value

Added image.
## Remarks


This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method


Adds image from a memory stream.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Memory stream. |

### Return Value

Added image.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method


Add an image to a presentation from stream.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image from. |

### Return Value

Added image.
## Remarks


This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method


Creates and adds an image to a presentation from stream.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image file from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### Return Value

Added [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method


Adds an image to a presentation from specified buffer.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Return Value

Added image.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method


Adds a copy of an image from an another presentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Source image. |

### Return Value

Added image.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method


Add an image to a presentation from SVG object.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG image object [ISvgImage](../../isvgimage/) |

### Return Value

Added image.

## See Also

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [Image](../../../system.drawing/image/)
* Class [IImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)