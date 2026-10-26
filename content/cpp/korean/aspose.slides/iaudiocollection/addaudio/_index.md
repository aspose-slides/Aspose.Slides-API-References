---
title: AddAudio()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 다른 프레젠테이션에서 오디오 파일을 복사하여 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) 메서드

다른 프레젠테이션에서 오디오 파일을 복사하여 추가합니다.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 원본 오디오. |

### 반환 값

추가된 오디오.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 프레젠테이션에 오디오를 생성하고 추가합니다.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 오디오를 추가할 스트림. |

### 반환 값

추가된 오디오.

Deprecated
:   AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior)를 사용하십시오. 이 메서드는 버전 17.10에서 제거될 예정입니다.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 메서드

스트림에서 프레젠테이션에 오디오를 생성하고 추가합니다.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 비디오 오디오를 추가할 스트림. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 스트림에 적용될 동작. |

### 반환 값

추가된 오디오.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) 메서드

바이트 배열에서 프레젠테이션에 오디오를 생성하고 추가합니다.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 바이트. |

### 반환 값

추가된 오디오.

## 참조

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)