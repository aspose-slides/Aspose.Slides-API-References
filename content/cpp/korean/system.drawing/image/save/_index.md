---
title: Save()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 이미지를 PNG 형식으로 지정된 파일에 저장합니다.
type: docs
weight: 1
url: /ko/system.drawing/image/save/
---
## Image::Save(const String\&) 메서드

현재 객체가 나타내는 이미지를 PNG 형식으로 지정된 파일에 저장합니다.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지를 저장할 파일의 이름 |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) 메서드

현재 객체가 나타내는 이미지를 지정된 형식으로 지정된 파일에 저장합니다.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지를 저장할 파일의 이름 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 이미지를 저장할 형식 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) 메서드

현재 객체가 나타내는 이미지를 지정된 형식으로 지정된 스트림에 저장합니다.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 이미지를 저장할 스트림 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 이미지를 저장할 형식 |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 메서드

현재 객체가 나타내는 이미지를 지정된 인코더와 인코더 매개변수를 사용하여 지정된 파일에 저장합니다.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지를 저장할 파일의 이름 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 사용할 인코더 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 사용할 인코더의 매개변수 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 메서드

현재 객체가 나타내는 이미지를 지정된 인코더와 인코더 매개변수를 사용하여 지정된 스트림에 저장합니다.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 이미지를 저장할 스트림 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 사용할 인코더 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 사용할 인코더의 매개변수 |

## 참조

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Image](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)