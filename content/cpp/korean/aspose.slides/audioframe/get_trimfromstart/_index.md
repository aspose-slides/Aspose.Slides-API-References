---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API 참조
description: 재생 중 미디어 시작 부분에서 제거될 시간 길이를 밀리초 단위로 지정합니다. 읽기 전용 float.
type: docs
weight: 404
url: /ko/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() 메서드


재생 중 미디어 시작 부분에서 제거될 시간 길이를 밀리초 단위로 지정합니다. 읽기 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 시작 트리밍 시간을 1.5초로 설정
audioFrame->set_TrimFromStart(1500.0f);
```

## 참고

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)