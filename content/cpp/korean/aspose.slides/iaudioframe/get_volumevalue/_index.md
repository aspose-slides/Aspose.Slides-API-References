---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API 참조
description: 오디오 볼륨을 퍼센트 단위로 반환합니다. float 형식으로 읽을 수 있습니다.
type: docs
weight: 378
url: /ko/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() 메서드


오디오 볼륨을 퍼센트 단위로 반환합니다. **float** 형식으로 읽을 수 있습니다.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## 비고


예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [IAudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)