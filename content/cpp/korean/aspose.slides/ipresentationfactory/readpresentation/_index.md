---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API 참조
description: 배열에서 기존 프레젠테이션을 읽습니다
type: docs
weight: 27
url: /ko/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 메서드

배열에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽을 배열 |

### 반환값

프레젠테이션 읽기

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 메서드

추가 로드 옵션과 함께 배열에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽을 배열 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환값

프레젠테이션 읽기

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 읽을 입력 스트림 |

### 반환값

프레젠테이션 읽기

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 메서드

추가 로드 옵션과 함께 스트림에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 읽을 입력 스트림 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환값

프레젠테이션 읽기

## IPresentationFactory::ReadPresentation(System::String) 메서드

파일에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 파일 이름 |

### 반환값

프레젠테이션 읽기

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 메서드

추가 로드 옵션과 함께 파일에서 기존 프레젠테이션을 읽습니다

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 파일 이름 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환값

프레젠테이션 읽기

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [IPresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)