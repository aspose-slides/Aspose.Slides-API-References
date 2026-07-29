---
title: Save()
second_title: Aspose.Slides för C++ API-referens
description: Sparar bilden som representeras av det aktuella objektet till den angivna filen i PNG-format.
type: docs
weight: 1
url: /sv/system.drawing/image/save/
---
## Image::Save(const String\&) metod


Sparar bilden som representeras av det aktuella objektet till den angivna filen i PNG-format.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Namnet på filen som bilden ska sparas till |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metod


Sparar bilden som representeras av det aktuella objektet till den angivna filen i det angivna formatet.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Namnet på filen som bilden ska sparas till |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Ett format att spara bilden i |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metod


Sparar bilden som representeras av det aktuella objektet till den angivna strömmen i det angivna formatet.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | En ström att spara bilden till |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Ett format att spara bilden i |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metod


Sparar bilden som representeras av det aktuella objektet till den angivna filen med den angivna kodaren och kodarparametrarna.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Namnet på filen som bilden ska sparas till |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Kodaren som ska användas |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametrarna för kodaren som ska användas |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metod


Sparar bilden som representeras av det aktuella objektet till den angivna strömmen med den angivna kodaren och kodarparametrarna.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | En ström att spara bilden till |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Kodaren som ska användas |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametrarna för kodaren som ska användas |

## Se även

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Klass [String](../../../system/string/)
* Klass [Image](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)