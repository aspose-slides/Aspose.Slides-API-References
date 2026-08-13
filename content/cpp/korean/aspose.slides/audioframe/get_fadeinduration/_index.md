---
title: get_FadeInDuration()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 미디어의 초기 페이드인 지속 시간을 밀리초 단위로 지정합니다. 읽기 float.
type: docs
weight: 326
url: /ko/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() 메서드


미디어의 초기 페이드인 지속 시간을 밀리초 단위로 지정합니다. 읽기 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 시작 페이드 지속 시간을 200ms로 설정
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)