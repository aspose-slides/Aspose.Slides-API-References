---
title: Save()
second_title: Referência da API Aspose.Slides para C++
description: Salva a imagem representada pelo objeto atual no arquivo especificado no formato PNG.
type: docs
weight: 1
url: /pt/system.drawing/image/save/
---
## Image::Save(const String\&) método

Salva a imagem representada pelo objeto atual no arquivo especificado no formato PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | O nome do arquivo onde a imagem será salva |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) método

Salva a imagem representada pelo objeto atual no arquivo especificado no formato especificado.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | O nome do arquivo onde a imagem será salva |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Um formato para salvar a imagem |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) método

Salva a imagem representada pelo objeto atual no fluxo especificado no formato especificado.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Um fluxo para salvar a imagem |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Um formato para salvar a imagem |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) método

Salva a imagem representada pelo objeto atual no arquivo especificado usando o codificador e os parâmetros de codificador especificados.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | O nome do arquivo onde a imagem será salva |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | O codificador a ser usado |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Os parâmetros do codificador a ser usado |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) método

Salva a imagem representada pelo objeto atual no fluxo especificado usando o codificador e os parâmetros de codificador especificados.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Um fluxo para salvar a imagem |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | O codificador a ser usado |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Os parâmetros do codificador a ser usado |

## Veja também

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Classe [String](../../../system/string/)
* Classe [Image](../)
* Classe [Stream](../../../system.io/stream/)
* Espaço de nomes [System::Drawing](../../)
* Library [Aspose.Slides](../../../)