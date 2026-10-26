---
title: Save()
second_title: Aspose.Slides для C++ справочник API
description: Сохраняет изображение, представленное текущим объектом, в указанный файл в формате PNG.
type: docs
weight: 1
url: /ru/system.drawing/image/save/
---
## Image::Save(const String\&) метод

Сохраняет изображение, представленное текущим объектом, в указанный файл в формате PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла, в который сохраняется изображение |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) метод

Сохраняет изображение, представленное текущим объектом, в указанный файл в указанном формате.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла, в который сохраняется изображение |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Формат, в котором сохраняется изображение |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) метод

Сохраняет изображение, представленное текущим объектом, в указанный поток в указанном формате.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Поток, в который сохраняется изображение |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Формат, в котором сохраняется изображение |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) метод

Сохраняет изображение, представленное текущим объектом, в указанный файл, используя указанный кодировщик и параметры кодировщика.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла, в который сохраняется изображение |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Кодировщик, который будет использоваться |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Параметры кодировщика, которые будут использоваться |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) метод

Сохраняет изображение, представленное текущим объектом, в указанный поток, используя указанный кодировщик и параметры кодировщика.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Поток, в который сохраняется изображение |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Кодировщик, который будет использоваться |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Параметры кодировщика, которые будут использоваться |

## См. также

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [String](../../../system/string/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)