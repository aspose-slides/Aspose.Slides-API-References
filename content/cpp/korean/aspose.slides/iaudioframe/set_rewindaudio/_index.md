---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오디오가 재생 후 자동으로 시작 위치로 되감기되는지 여부를 결정합니다. bool를 씁니다.
type: docs
weight: 248
url: /ko/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) 메서드


오디오가 재생 후 자동으로 시작 위치로 되감기되는지 여부를 결정합니다. **bool**를 씁니다.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 오디오 프레임 추가
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 오디오를 모든 슬라이드에서 재생하도록 설정
audioFrame->set_PlayAcrossSlides(true);

// 재생 후 오디오가 자동으로 시작으로 되감기되도록 설정
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 참조

* 클래스 [IAudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)