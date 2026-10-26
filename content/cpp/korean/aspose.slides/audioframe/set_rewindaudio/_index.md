---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 재생 후 오디오가 시작점으로 자동 되돌아가는지 여부를 결정합니다. bool을 씁니다.
type: docs
weight: 248
url: /ko/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) 메서드


재생 후 오디오가 시작점으로 자동 되돌아가는지 여부를 결정합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 참고

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)