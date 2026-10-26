---
title: SaveAdd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이전 호출에서 Save() 메서드에 지정된 파일 또는 스트림에 프레임을 추가합니다.
type: docs
weight: 14
url: /ko/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) 메서드

[Save()](../save/) 메서드에 대한 이전 호출에서 지정된 파일 또는 스트림에 프레임을 추가합니다.

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 사용할 인코더의 매개변수 |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) 메서드

[Save()](../save/) 메서드에 대한 이전 호출에서 지정된 파일 또는 스트림에 프레임을 추가합니다.

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | [Image](../) 객체이며 추가할 프레임을 포함합니다 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 사용할 인코더의 매개변수 |

## 참조

* 타입 정의 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)