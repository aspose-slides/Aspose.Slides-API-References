---
title: Save()
second_title: Aspose.Slides for C++ API Reference
description: Saves the image to a file.
type: docs
weight: 40
url: /aspose.slides/iimage/save/
---
## IImage::Save(System::String) method


Saves the image to a file.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | The path to the file where the image will be saved. |

## IImage::Save(System::String, ImageFormat) method


Saves the image to a file in the specified format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | The path to the file where the image will be saved. |
| format | [ImageFormat](../../imageformat/) | The image format. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) method


Saves the image to a stream in the specified format.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The stream where the image will be saved. |
| format | [ImageFormat](../../imageformat/) | The image format. |

## IImage::Save(System::String, ImageFormat, int32_t) method


Saves the image to a file in the specified format and quality.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | The path to the file where the image will be saved. |
| format | [ImageFormat](../../imageformat/) | The image format. |
| quality | **int32_t** | The quality of the saved image (0 to 100). 

 This parameter only affects saving in [ImageFormat::Jpeg](../../imageformat/); for all other formats, it is ignored. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) method


Saves the image to a stream in the specified format and quality.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The stream where the image will be saved. |
| format | [ImageFormat](../../imageformat/) | The image format. |
| quality | **int32_t** | The quality of the saved image (0 to 100). 

 This parameter only affects saving in [ImageFormat::Jpeg](../../imageformat/); for all other formats, it is ignored. |

## See Also

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)