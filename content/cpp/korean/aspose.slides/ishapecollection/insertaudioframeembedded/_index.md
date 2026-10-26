---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 참조
description: 임베디드 WAV 파일이 포함된 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 임베디드 오디오는 Presentation.Audios 컬렉션에 추가됩니다.
type: docs
weight: 261
url: /ko/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


임베디드 WAV 파일이 포함된 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 임베디드 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작되는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 단위는 포인트입니다. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림입니다. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) method


기존 Presentation.Audios 목록의 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작되는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 단위는 포인트입니다. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios 컬렉션에서 임베드할 [IAudio](../../iaudio/) 인스턴스입니다. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IShapeCollection](../)
* 클래스 [IAudio](../../iaudio/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)