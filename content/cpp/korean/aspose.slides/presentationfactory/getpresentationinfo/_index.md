---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API 참조
description: 파일에서 새 PresentationInfo 객체를 만들고 프레젠테이션에 바인딩합니다.
type: docs
weight: 27
url: /ko/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) 메서드

파일에서 새 [PresentationInfo](../../presentationinfo/) 객체를 만들고 프레젠테이션에 바인딩합니다.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 파일. |

### 반환값

[Presentation](../../presentation/) 정보를 프레젠테이션에 바인딩합니다.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 새 [PresentationInfo](../../presentationinfo/) 객체를 만들고 프레젠테이션에 바인딩합니다. 지정된 스트림의 프레젠테이션에 대한 정보를 가져옵니다.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 스트림. |

### 반환값

[Presentation](../../presentation/) 정보를 프레젠테이션에 바인딩합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPresentationInfo](../../ipresentationinfo/)
* 클래스 [String](../../../system/string/)
* 클래스 [PresentationFactory](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)