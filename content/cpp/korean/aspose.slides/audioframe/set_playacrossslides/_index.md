---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides for C++ API 참조
description: 오디오가 슬라이드 전체에서 재생되는지 여부를 결정합니다. bool을 씁니다.
type: docs
weight: 222
url: /ko/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) 메서드


오디오가 슬라이드 전반에 걸쳐 재생되는지 여부를 결정합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 오디오 프레임 추가
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 오디오를 슬라이드 전반에 걸쳐 재생하도록 설정
audioFrame->set_PlayAcrossSlides(true);

// 오디오가 재생 후 자동으로 시작으로 되감도록 설정
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 참고

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)