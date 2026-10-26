---
title: Save()
second_title: Référence de l'API Aspose.Slides for C++
description: Enregistre l'image représentée par l'objet actuel dans le fichier spécifié au format PNG.
type: docs
weight: 1
url: /fr/system.drawing/image/save/
---
## Image::Save(const String\&) méthode

Enregistre l'image représentée par l'objet actuel dans le fichier spécifié au format PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier dans lequel enregistrer l'image |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) méthode

Enregistre l'image représentée par l'objet actuel dans le fichier spécifié au format indiqué.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier dans lequel enregistrer l'image |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un format dans lequel enregistrer l'image |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) méthode

Enregistre l'image représentée par l'objet actuel dans le flux spécifié au format indiqué.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flux dans lequel enregistrer l'image |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un format dans lequel enregistrer l'image |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) méthode

Enregistre l'image représentée par l'objet actuel dans le fichier spécifié en utilisant l'encodeur et les paramètres d'encodeur indiqués.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier dans lequel enregistrer l'image |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | L'encodeur à utiliser |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Les paramètres de l'encodeur à utiliser |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) méthode

Enregistre l'image représentée par l'objet actuel dans le flux spécifié en utilisant l'encodeur et les paramètres d'encodeur indiqués.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flux dans lequel enregistrer l'image |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | L'encodeur à utiliser |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Les paramètres de l'encodeur à utiliser |

## Voir aussi

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Classe [String](../../../system/string/)
* Classe [Image](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [System::Drawing](../../)
* Library [Aspose.Slides](../../../)