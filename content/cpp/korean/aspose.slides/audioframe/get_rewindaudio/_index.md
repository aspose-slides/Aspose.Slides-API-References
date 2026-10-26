---
title: get_RewindAudio()
second_title: Aspose.Slides for C++ API 참조
description: 오디오가 재생 후 자동으로 시작점으로 되감기되는지를 결정합니다. 읽기 bool.
type: docs
weight: 235
url: /ko/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() 메서드


오디오가 재생 후 자동으로 시작점으로 되감기되는지를 결정합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
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