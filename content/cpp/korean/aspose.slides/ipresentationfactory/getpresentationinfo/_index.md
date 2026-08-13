---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 파일의 프레젠테이션에 대한 정보를 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) 메서드

지정된 파일에 있는 프레젠테이션에 대한 정보를 가져옵니다.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 파일. |

### 반환값

[Presentation](../../presentation/) 정보

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 메서드

지정된 스트림에 있는 프레젠테이션에 대한 정보를 가져옵니다.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 스트림. |

### 반환값

[Presentation](../../presentation/) 정보.

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPresentationInfo](../../ipresentationinfo/)
* 클래스 [String](../../../system/string/)
* 클래스 [IPresentationFactory](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)