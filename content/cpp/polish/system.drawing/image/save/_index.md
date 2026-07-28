---
title: Save()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w formacie PNG.
type: docs
weight: 1
url: /pl/system.drawing/image/save/
---
## Image::Save(const String\&) metoda


Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w formacie PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku, do którego ma zostać zapisany obraz |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metoda


Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w podanym formacie.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku, do którego ma zostać zapisany obraz |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Format, w którym ma zostać zapisany obraz |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metoda


Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia w podanym formacie.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego ma zostać zapisany obraz |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Format, w którym ma zostać zapisany obraz |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metoda


Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku przy użyciu podanego kodera i parametrów kodera.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku, do którego ma zostać zapisany obraz |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Koder do użycia |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry kodera do użycia |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metoda


Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia przy użyciu podanego kodera i parametrów kodera.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego ma zostać zapisany obraz |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Koder do użycia |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry kodera do użycia |

## Zobacz także

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Klasa [String](../../../system/string/)
* Klasa [Image](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)