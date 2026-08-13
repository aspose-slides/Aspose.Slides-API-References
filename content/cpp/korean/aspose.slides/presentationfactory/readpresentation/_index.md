---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열에서 기존 프레젠테이션을 읽습니다
type: docs
weight: 40
url: /ko/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 메서드


배열에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽을 배열 |

### 반환 값

읽은 프레젠테이션


## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 메서드


추가 로드 옵션과 함께 배열에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽을 배열 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환 값

읽은 프레젠테이션


## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 메서드


스트림에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 읽을 입력 스트림 |

### 반환 값

읽은 프레젠테이션


## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 메서드


추가 로드 옵션과 함께 스트림에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 읽을 입력 스트림 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환 값

읽은 프레젠테이션


## PresentationFactory::ReadPresentation(System::String) 메서드


파일에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 파일 이름 |

### 반환 값

읽은 프레젠테이션


## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 메서드


추가 로드 옵션과 함께 파일에서 기존 프레젠테이션을 읽습니다

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 파일 이름 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환 값

읽은 프레젠테이션


## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IPresentation](../../ipresentation/)
* 클래스 [PresentationFactory](../)
* 클래스 [ILoadOptions](../../iloadoptions/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)