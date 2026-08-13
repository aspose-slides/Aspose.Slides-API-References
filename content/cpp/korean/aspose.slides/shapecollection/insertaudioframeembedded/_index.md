---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides C++용 API 참조
description: "새 오디오 프레임을 생성하고 삽입된 WAV 파일을 포함시킨 후, 지정된 인덱스에 shape 컬렉션에 삽입합니다. 삽입된 오디오는 Presentation::get_Audios 컬렉션에 추가됩니다."
type: docs
weight: 300
url: /ko/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 메서드

새 오디오 프레임을 생성하고 삽입된 WAV 파일을 포함시킨 후, 지정된 인덱스에 shape 컬렉션에 삽입합니다. 삽입된 오디오는 [Presentation::get_Audios](../../presentation/get_audios/) 컬렉션에 추가됩니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 삽입할 WAV 오디오 데이터를 포함하는 입력 스트림. |

### 반환 값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) 메서드

기존 [Presentation::get_Audios](../../presentation/get_audios/) 목록의 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 삽입할 [IAudio](../../iaudio/) 컬렉션의 [Presentation::get_Audios](../../presentation/get_audios/) 인스턴스. |

### 반환 값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [ShapeCollection](../)
* 클래스 [IAudio](../../iaudio/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)