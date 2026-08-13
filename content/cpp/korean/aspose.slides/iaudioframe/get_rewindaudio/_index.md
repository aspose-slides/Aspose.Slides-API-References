---
title: get_RewindAudio()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오디오가 재생 후 자동으로 시작 지점으로 되감겨지는지 여부를 결정합니다. 읽기 bool.
type: docs
weight: 235
url: /ko/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() 메서드


오디오가 재생 후 자동으로 시작 지점으로 되감겨지는지 여부를 결정합니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 오디오 프레임 추가
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 슬라이드 전체에서 오디오 재생 설정
audioFrame->set_PlayAcrossSlides(true);

// 재생 후 자동으로 시작 지점으로 오디오 되감기 설정
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 참조

* 클래스 [IAudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)