---
title: AddVideo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) 메서드

다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 소스 비디오. |

### 반환 값

추가된 비디오.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 메서드

스트림에서 프레젠테이션에 비디오를 생성하고 추가합니다.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 비디오 파일을 추가할 스트림. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 스트림에 적용될 동작. |

### 반환 값

추가된 [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) 메서드

바이트 배열에서 프레젠테이션에 비디오를 생성하고 추가합니다.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) 바이트. |

### 반환 값

추가된 비디오.

## 참고

* 열거형 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IVideo](../../ivideo/)
* 클래스 [VideoCollection](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)