---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오디오 볼륨을 백분율로 반환합니다. 읽기 float.
type: docs
weight: 378
url: /ko/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() 메서드


오디오 볼륨을 백분율로 반환합니다. 읽기 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 시작 페이드의 지속 시간을 200ms로 설정
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)