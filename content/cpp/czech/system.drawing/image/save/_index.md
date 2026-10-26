---
title: Save()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Uloží obraz reprezentovaný aktuálním objektem do zadaného souboru ve formátu PNG.
type: docs
weight: 1
url: /cs/system.drawing/image/save/
---
## Image::Save(const String\&) metoda

Uloží obraz reprezentovaný aktuálním objektem do zadaného souboru ve formátu PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, do kterého se má obraz uložit |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metoda

Uloží obraz reprezentovaný aktuálním objektem do zadaného souboru ve zvoleném formátu.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, do kterého se má obraz uložit |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Formát, ve kterém se má obraz uložit |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metoda

Uloží obraz reprezentovaný aktuálním objektem do určeného proudu ve zvoleném formátu.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého se má obraz uložit |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Formát, ve kterém se má obraz uložit |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metoda

Uloží obraz reprezentovaný aktuálním objektem do zadaného souboru pomocí zvoleného enkodéru a parametrů enkodéru.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, do kterého se má obraz uložit |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Enkodér, který se má použít |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry enkodéru, které se mají použít |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metoda

Uloží obraz reprezentovaný aktuálním objektem do určeného proudu pomocí zvoleného enkodéru a parametrů enkodéru.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého se má obraz uložit |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Enkodér, který se má použít |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry enkodéru, které se mají použít |

## Viz také

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Třída [String](../../../system/string/)
* Třída [Image](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)