---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 재생 중에 미디어 시작 부분에서 제거되는 시간 길이를 밀리초 단위로 지정합니다. float을 기록합니다.
type: docs
weight: 417
url: /ko/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) 메서드


재생 중에 미디어 시작 부분에서 제거되는 시간 길이를 밀리초 단위로 지정합니다. **float**을(를) 기록합니다.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
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

## 참조

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)