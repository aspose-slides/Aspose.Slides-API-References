---
title: Save()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象表示的图像保存到指定文件，采用 PNG 格式。
type: docs
weight: 1
url: /zh/system.drawing/image/save/
---
## Image::Save(const String\&) 方法

将当前对象表示的图像保存到指定文件，采用 PNG 格式。

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 保存图像的文件名 |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) 方法

将当前对象表示的图像保存到指定文件，采用指定的格式。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 保存图像的文件名 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 要保存图像的格式 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) 方法

将当前对象表示的图像保存到指定流，采用指定的格式。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 用于保存图像的流 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 要保存图像的格式 |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 方法

将当前对象表示的图像保存到指定文件，使用指定的编码器和编码器参数。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 保存图像的文件名 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 要使用的编码器 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的编码器参数 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 方法

将当前对象表示的图像保存到指定流，使用指定的编码器和编码器参数。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 用于保存图像的流 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 要使用的编码器 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 使用的编码器参数 |

## 参见

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 类 [String](../../../system/string/)
* 类 [Image](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)