---
title: Save()
second_title: Aspose.Slides C++ API Referansı
description: Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya PNG formatında kaydeder.
type: docs
weight: 1
url: /tr/system.drawing/image/save/
---
## Image::Save(const String\&) metod

Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya PNG formatında kaydeder.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Görüntünün kaydedileceği dosyanın adı |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metod

Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya istenen formatta kaydeder.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Görüntünün kaydedileceği dosyanın adı |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Görüntünün kaydedileceği format |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metod

Geçerli nesne tarafından temsil edilen görüntüyü belirtilen akışa istenen formatta kaydeder.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Görüntünün kaydedileceği akış |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Görüntünün kaydedileceği format |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metod

Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya, belirtilen kodlayıcı ve kodlayıcı parametreleri kullanarak kaydeder.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Görüntünün kaydedileceği dosyanın adı |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Kullanılacak kodlayıcı |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Kullanılacak kodlayıcının parametreleri |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metod

Geçerli nesne tarafından temsil edilen görüntüyü belirtilen akışa, belirtilen kodlayıcı ve kodlayıcı parametreleri kullanarak kaydeder.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Görüntünün kaydedileceği akış |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Kullanılacak kodlayıcı |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Kullanılacak kodlayıcının parametreleri |

## Bakınız

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [String](../../../system/string/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)