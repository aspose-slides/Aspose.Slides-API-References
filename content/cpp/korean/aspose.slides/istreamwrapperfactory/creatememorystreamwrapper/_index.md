---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides C++ API 레퍼런스
description: MemoryStream 래퍼를 생성합니다.
type: docs
weight: 1
url: /ko/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() 메서드


MemoryStream 래퍼를 생성합니다.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```


### 반환 값

COM 인터페이스 [IStreamWrapper](../../istreamwrapper/)용 스트림 래퍼

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) 메서드


지정된 바이트 배열을 기반으로 MemoryStream 래퍼를 생성합니다.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 **uint8_t**[] |

### 반환 값

COM 인터페이스 [IStreamWrapper](../../istreamwrapper/)용 스트림 래퍼

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IStreamWrapper](../../istreamwrapper/)
* 클래스 [IStreamWrapperFactory](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)