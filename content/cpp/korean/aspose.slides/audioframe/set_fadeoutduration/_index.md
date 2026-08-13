---
title: set_FadeOutDuration()
second_title: Aspose.Slides C++ API 참조
description: 미디어 종료 페이드 아웃에 대한 시간 지속 시간을 밀리초 단위로 지정합니다. float를 씁니다.
type: docs
weight: 365
url: /ko/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) 메서드


미디어의 종료 페이드 아웃에 대한 시간 지속 시간을 밀리초 단위로 지정합니다. **float**를 씁니다.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 종료 페이드 아웃 지속 시간을 500ms로 설정
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)