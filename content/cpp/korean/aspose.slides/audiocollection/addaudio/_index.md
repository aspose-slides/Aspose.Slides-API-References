---
title: AddAudio()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 다른 프레젠테이션에서 오디오 파일의 복사본을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) 메서드

다른 프레젠테이션에서 오디오 파일의 복사본을 추가합니다.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 원본 오디오. |

### 반환값

추가된 오디오.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 오디오를 생성하여 프레젠테이션에 추가합니다.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 오디오를 추가할 스트림. |

### 반환값

추가된 오디오.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 메서드

스트림에서 오디오를 생성하여 프레젠테이션에 추가합니다.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 비디오 오디오를 추가할 스트림. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 스트림에 적용될 동작. |

### 반환값

추가된 오디오.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) 메서드

바이트 배열에서 오디오를 생성하여 프레젠테이션에 추가합니다.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) 바이트. |

### 반환값

추가된 오디오.

## 참고

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)