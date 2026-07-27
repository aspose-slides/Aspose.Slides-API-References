---
title: Save()
second_title: Referencia de la API de Aspose.Slides para C++
description: Guarda la imagen representada por el objeto actual en el archivo especificado en formato PNG.
type: docs
weight: 1
url: /es/system.drawing/image/save/
---
## Image::Save(const String\&) método

Guarda la imagen representada por el objeto actual en el archivo especificado en formato PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo donde se guardará la imagen |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) método

Guarda la imagen representada por el objeto actual en el archivo especificado en el formato indicado.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo donde se guardará la imagen |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un formato en el que guardar la imagen |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) método

Guarda la imagen representada por el objeto actual en el flujo especificado en el formato indicado.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flujo donde guardar la imagen |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Un formato en el que guardar la imagen |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) método

Guarda la imagen representada por el objeto actual en el archivo especificado usando el codificador y los parámetros de codificador indicados.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo donde se guardará la imagen |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | El codificador a utilizar |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Los parámetros del codificador a utilizar |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) método

Guarda la imagen representada por el objeto actual en el flujo especificado usando el codificador y los parámetros de codificador indicados.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flujo donde guardar la imagen |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | El codificador a utilizar |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Los parámetros del codificador a utilizar |

## Ver también

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Clase [String](../../../system/string/)
* Clase [Image](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [System::Drawing](../../)
* Library [Aspose.Slides](../../../)