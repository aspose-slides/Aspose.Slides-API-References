---
title: Save()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de afbeelding die door het huidige object wordt weergegeven op in het opgegeven bestand in PNG-formaat.
type: docs
weight: 1
url: /nl/system.drawing/image/save/
---
## Image::Save(const String\&) methode


Slaat de afbeelding die door het huidige object wordt weergegeven op in het opgegeven bestand in PNG-formaat.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De naam van het bestand waarin de afbeelding moet worden opgeslagen |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) methode


Slaat de afbeelding die door het huidige object wordt weergegeven op in het opgegeven bestand in het opgegeven formaat.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De naam van het bestand waarin de afbeelding moet worden opgeslagen |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Een formaat waarin de afbeelding moet worden opgeslagen |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) methode


Slaat de afbeelding die door het huidige object wordt weergegeven op in de opgegeven stream in het opgegeven formaat.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Een stream waarin de afbeelding moet worden opgeslagen |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Een formaat waarin de afbeelding moet worden opgeslagen |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) methode


Slaat de afbeelding die door het huidige object wordt weergegeven op in het opgegeven bestand met de opgegeven encoder en encoder-parameters.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De naam van het bestand waarin de afbeelding moet worden opgeslagen |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | De te gebruiken encoder |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | De parameters van de te gebruiken encoder |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) methode


Slaat de afbeelding die door het huidige object wordt weergegeven op in de opgegeven stream met de opgegeven encoder en encoder-parameters.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Een stream waarin de afbeelding moet worden opgeslagen |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | De te gebruiken encoder |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | De parameters van de te gebruiken encoder |

## Zie ook

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Klasse [String](../../../system/string/)
* Klasse [Image](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [System::Drawing](../../)
* Library [Aspose.Slides](../../../)