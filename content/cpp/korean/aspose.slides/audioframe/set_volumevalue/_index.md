---
title: set_VolumeValue()
second_title: Aspose.Slides for C++ API 참조
description: 퍼센트 단위로 오디오 볼륨을 설정합니다. float 형식으로 작성합니다.
type: docs
weight: 391
url: /ko/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) 메서드


퍼센트 단위로 오디오 볼륨을 설정합니다. **float** 형식으로 작성합니다.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 시작 페이드의 지속 시간을 200ms로 설정합니다
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)