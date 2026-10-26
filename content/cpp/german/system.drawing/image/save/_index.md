---
title: Save()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei im PNG-Format.
type: docs
weight: 1
url: /de/system.drawing/image/save/
---
## Image::Save(const String\&) Methode

Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei im PNG-Format.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Datei, in die das Bild gespeichert werden soll |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) Methode

Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei im angegebenen Format.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Datei, in die das Bild gespeichert werden soll |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Ein Format, in dem das Bild gespeichert werden soll |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) Methode

Speichert das durch das aktuelle Objekt dargestellte Bild in den angegebenen Stream im angegebenen Format.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Ein Stream, in den das Bild gespeichert werden soll |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Ein Format, in dem das Bild gespeichert werden soll |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) Methode

Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei unter Verwendung des angegebenen Encoders und der Encoder-Parameter.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Datei, in die das Bild gespeichert werden soll |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Der zu verwendende Encoder |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Die zu verwendenden Encoder-Parameter |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) Methode

Speichert das durch das aktuelle Objekt dargestellte Bild in den angegebenen Stream unter Verwendung des angegebenen Encoders und der Encoder-Parameter.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Ein Stream, in den das Bild gespeichert werden soll |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Der zu verwendende Encoder |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Die zu verwendenden Encoder-Parameter |

## Siehe auch

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Klasse [String](../../../system/string/)
* Klasse [Image](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)