---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API Reference
description: Replaces image data.
type: docs
weight: 131
url: /aspose.slides/ippimage/replaceimage/
---
## IPPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) method


Replaces image data.

```cpp
virtual void Aspose::Slides::IPPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The new image's data. |

## IPPImage::ReplaceImage(System::SharedPtr\<System::Drawing::Image\>) method


Replaces image.

```cpp
virtual void Aspose::Slides::IPPImage::ReplaceImage(System::SharedPtr<System::Drawing::Image> newImage)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Image](../../../system.drawing/image/)\> | The new image. |

Deprecated
:   Use ReplaceImage(IImage newImage) method instead. The method will be removed after release of version 24.7.

## IPPImage::ReplaceImage(System::SharedPtr\<IImage\>) method


Replaces image.

```cpp
virtual void Aspose::Slides::IPPImage::ReplaceImage(System::SharedPtr<IImage> newImage)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | The new image. |

## IPPImage::ReplaceImage(System::SharedPtr\<IPPImage\>) method


Replaces image.

```cpp
virtual void Aspose::Slides::IPPImage::ReplaceImage(System::SharedPtr<IPPImage> newImage)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../)\> | The new [IPPImage](../). |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../)
* Class [Image](../../../system.drawing/image/)
* Class [IImage](../../iimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)