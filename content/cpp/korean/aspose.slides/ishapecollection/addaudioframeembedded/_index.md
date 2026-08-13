---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 임베디드 WAV 파일이 포함된 새 오디오 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다. 임베디드 오디오는 Presentation.Audios 컬렉션에 추가됩니다.
type: docs
weight: 248
url: /ko/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

새 오디오 프레임을 만들고 임베디드 WAV 파일과 함께 shape collection의 끝에 추가합니다. 임베디드 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 단위는 포인트입니다. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림입니다. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

새 오디오 프레임을 만들고 Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 shape collection의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 단위는 포인트입니다. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios 컬렉션에 있는 [IAudio](../../iaudio/) 인스턴스입니다. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IShapeCollection](../)
* 클래스 [IAudio](../../iaudio/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)