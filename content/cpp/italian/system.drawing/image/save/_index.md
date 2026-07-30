---
title: Save()
second_title: Riferimento API Aspose.Slides per C++
description: Salva l'immagine rappresentata dall'oggetto corrente nel file specificato in formato PNG.
type: docs
weight: 1
url: /it/system.drawing/image/save/
---
## Image::Save(const String\&) metodo


Salva l'immagine rappresentata dall'oggetto corrente nel file specificato in formato PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file in cui salvare l'immagine |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metodo


Salva l'immagine rappresentata dall'oggetto corrente nel file specificato nel formato specificato.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file in cui salvare l'immagine |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un formato in cui salvare l'immagine |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metodo


Salva l'immagine rappresentata dall'oggetto corrente nello stream specificato nel formato specificato.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flusso in cui salvare l'immagine |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un formato in cui salvare l'immagine |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metodo


Salva l'immagine rappresentata dall'oggetto corrente nel file specificato usando il codificatore e i parametri del codificatore specificati.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file in cui salvare l'immagine |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Il codificatore da utilizzare |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | I parametri del codificatore da utilizzare |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metodo


Salva l'immagine rappresentata dall'oggetto corrente nello stream specificato usando il codificatore e i parametri del codificatore specificati.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flusso in cui salvare l'immagine |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Il codificatore da utilizzare |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | I parametri del codificatore da utilizzare |

## Vedi anche

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Classe [String](../../../system/string/)
* Classe [Image](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)