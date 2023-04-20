---
title: Save()
second_title: Aspose.Slides for C++ API Reference
description: Saves the image represented by the current object to the specified file in PNG format.
type: docs
weight: 1
url: /cpp/system.drawing/image/save/
---
## Image::Save(const String\&) method


Saves the image represented by the current object to the specified file in PNG format.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The name of the file to save the image to |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) method


Saves the image represented by the current object to the specified file in the specified format.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The name of the file to save the image to |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | A format to save the image in |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) method


Saves the image represented by the current object to the specified stream in the specified format.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | A stream to save the image to |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | A format to save the image in |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Saves the image represented by the current object to the specified file using the specified encoder and encoder parameters.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The name of the file to save the image to |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | The encoder to use |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | The parameters of the encoder to use |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Saves the image represented by the current object to the specified stream using the specified encoder and encoder parameters.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | A stream to save the image to |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | The encoder to use |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | The parameters of the encoder to used |

## See Also

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [String](../../../system/string/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)