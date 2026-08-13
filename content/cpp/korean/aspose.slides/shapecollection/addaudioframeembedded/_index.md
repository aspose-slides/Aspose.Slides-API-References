---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "새 오디오 프레임을 임베디드된 WAV 파일과 함께 생성하고 이를 shape 컬렉션의 끝에 추가합니다. 임베디드 오디오는 Presentation::get_Audios 컬렉션에 추가됩니다."
type: docs
weight: 287
url: /ko/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 메서드


새 오디오 프레임을 임베디드 WAV 파일과 함께 생성하고 이를 shape 컬렉션의 끝에 추가합니다. 임베디드 오디오가 [Presentation::get_Audios](../../presentation/get_audios/) 컬렉션에 추가됩니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x-좌표, 포인트 단위. |
| y | **float** | 새 오디오 프레임의 y-좌표, 포인트 단위. |
| width | **float** | 새 오디오 프레임의 너비, 포인트 단위. |
| height | **float** | 새 오디오 프레임의 높이, 포인트 단위. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 비고



다음 예제는 [Audio](../../audio/) 프레임을 만드는 방법을 보여줍니다. 
```cpp
// 프레젠테이션 파일을 나타내는 프레젠테이션 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();

// 첫 번째 슬라이드를 가져옵니다
auto slide = pres->get_Slides()->idx_get(0);
// wav 사운드 파일을 스트림으로 로드합니다
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// 오디오 프레임을 추가합니다
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// 오디오의 재생 모드와 볼륨을 설정합니다
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// PowerPoint 파일을 디스크에 저장합니다
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) 메서드


기존 [Presentation::get_Audios](../../presentation/get_audios/) 목록의 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x-좌표, 포인트 단위. |
| y | **float** | 새 오디오 프레임의 y-좌표, 포인트 단위. |
| width | **float** | 새 오디오 프레임의 너비, 포인트 단위. |
| height | **float** | 새 오디오 프레임의 높이, 포인트 단위. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [Presentation::get_Audios](../../presentation/get_audios/) 컬렉션에 있는 [IAudio](../../iaudio/) 인스턴스. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)