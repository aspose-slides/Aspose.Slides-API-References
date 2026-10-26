---
title: get_TrimFromStart()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 재생 중에 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기 전용 float.
type: docs
weight: 404
url: /ko/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() 메서드

재생 중에 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기 전용 **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## 비고

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## 참조

* 클래스 [IAudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)